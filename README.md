# Credit Card Approval Prediction

A Team 3 project completed as part of the UNP ML Academic Internship. This project explores credit application data and builds classification models to predict approval outcomes.

## Project overview

The notebook contains the end-to-end machine-learning workflow:

- Data inspection, cleaning, and exploratory analysis
- Feature preparation and preprocessing
- Classification model development and comparison
- Cross-validation and hyperparameter tuning
- An Artificial Neural Network (ANN) experiment using TensorFlow
- Evaluation with classification metrics and confusion matrices

## Models explored

Logistic Regression, K-Nearest Neighbors, Decision Tree, Random Forest, XGBoost, Support Vector Machine, Gaussian Naive Bayes, and a TensorFlow-based ANN.

## Repository contents

| File | Description |
| --- | --- |
| `credit-card-approval-prediction.ipynb` | Main analysis and modelling notebook, including saved cell outputs |
| `credit card_dataset.csv` | Dataset used by the notebook |
| `requirements.txt` | Python dependencies |
| `Credit_Card_Approval_Presentation.pptx` | Project presentation |

## Getting started

1. Clone this repository.
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `credit-card-approval-prediction.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
4. Run the notebook from top to bottom if you want to reproduce the analysis. Existing saved outputs are included for reference.

The notebook expects the dataset file `credit card_dataset.csv` in the repository root.

## Team

This was a collaborative academic project completed by Team 3:

- Akula Siri
- K Jayadeva Satyavamsi
- P Harshit
- Peruri Ramya Sree

## Notes

- The notebook is committed with its saved outputs; the repository does not automatically execute notebooks on every push.
- Model results may vary with library versions and runtime environments.
- This is an educational modelling exercise, not a production credit-decision system. Real credit decisions require careful fairness, explainability, privacy, and regulatory review.
