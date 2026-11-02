# Credit Card Approval Prediction

An academic group project focused on exploring credit application data and building classification models to predict approval outcomes.

## Project overview

The notebook follows an end-to-end machine-learning workflow, including:
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
| `credit-card-approval-prediction.ipynb` | Main analysis and modelling notebook |
| `requirements.txt` | Python dependencies |

## Getting started

1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Obtain the original project CSV, named `credit card_dataset.csv`, from the course/internship source.
4. Place it in the repository root or in a folder named `data/`.
5. Open the notebook in Jupyter or Google Colab and run it from top to bottom.

**The dataset is not included** because its redistribution terms have not been established. Use the original authorised source and check its licence before sharing it.

## Academic context and attribution

This was completed as a **college group project associated with an academic internship**. The notebook represents collaborative work; it should not be interpreted as an individual project completed solely by the repository owner. Add the full team roster, mentor/institution details, and individual contributions here before presenting the repository as a final public record.

## Reproducibility notes

- The notebook's saved cell outputs have been cleared to keep the repository lightweight and encourage fresh execution.
- Model metrics may vary with library versions and runtime environments.
- This is an educational modelling exercise, not a production credit-decision system. Real credit decisions require careful fairness, explainability, privacy, and regulatory review.
