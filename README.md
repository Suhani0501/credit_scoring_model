## Credit Scoring Model
A Machine Learning project that predicts whether a customer is a **Good Risk** or **Bad Risk** for loan approval using historical financial information.

---
## Project Objective
The objective of this project is to build a Credit Scoring Model that predicts an individual's creditworthiness based on financial attributes using machine learning classification algorithms.

---
## Dataset
Dataset: German Credit Dataset
Features include:
- Age
- Sex
- Job
- Housing
- Saving Accounts
- Checking Account
- Credit Amount
- Duration
- Purpose

Target Variable:
- Risk
  - 0 = Bad Risk
  - 1 = Good Risk

---
## Data Preprocessing
The following preprocessing steps were performed:
- Loaded the dataset using Pandas
- Checked dataset shape and information
- Handled missing values
- Encoded categorical features
- Performed Feature Engineering
- Standardized numerical features using StandardScaler
- Split dataset into Training (80%) and Testing (20%)

---
## Feature Engineering
A new feature was created to improve model performance:

```python
Credit_per_Month = Credit amount / Duration
```
This represents the average monthly credit amount.

---
## Exploratory Data Analysis (EDA)
The following visualizations were generated:
- Risk Distribution
- Correlation Heatmap
- Feature Histograms
- Boxplots

All the generated visualizations are available in the *images/* folder.

---
## Machine Learning Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---
## Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 70.50% |
| Decision Tree | 73.00% |
| Random Forest | **75.00%** |

Random Forest achieved the highest accuracy among the three models.

---
## Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix
- ROC Curve (AUC)

---
## Project Structure

'''
Credit_Scoring_Model
│
├── dataset
│   └── german_credit_data.csv
│
├── images
│   ├── accuracy_comparison.png
│   ├── boxplots.png
│   ├── confusion_matrix.png
│   ├── correlation_heatmap.png
│   ├── histograms.png
│   ├── risk_distribution.png
│   └── roc_curve.png
│
├── Credit_Scoring.ipynb
├── README.md
└── requirements.txt
```

---
## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---
## How to Run
1. Clone this repository.
2. Install the required libraries:

```
pip install -r requirements.txt
```
3. Open the notebook:

```
Credit_Scoring.ipynb
```
4. Run all cells.

---
## Future Improvements
- Hyperparameter tuning
- Cross-validation
- Gradient Boosting algorithms (XGBoost, LightGBM)
- Web application deployment using Flask or Streamlit

---
## Suhani Sahoo

