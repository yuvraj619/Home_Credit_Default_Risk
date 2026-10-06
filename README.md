# Home Credit Default Risk

A machine learning project for **credit default risk prediction** using the Home Credit dataset. The goal is to analyze applicant and historical credit information and build a classification workflow that can help identify applicants who may be at higher risk of default.

## Project Overview

Credit risk assessment is a highly imbalanced classification problem: a relatively small proportion of applicants may experience payment difficulties, while the majority do not. This project explores the data, prepares the relevant features, and develops a predictive modelling workflow for default-risk classification.

The main analysis is contained in **`home_credit_default_risk.ipynb`**.

## Repository Contents

| File | Description |
|---|---|
| `home_credit_default_risk.ipynb` | Main Jupyter Notebook containing the analysis and modelling workflow |
| `credit_default_dataset.csv.zip` | Main credit/default dataset used by the project |
| `bureau.csv.zip` | Historical credit bureau information |
| `bureau_balance.csv.zip` | Monthly bureau-credit balance information |
| `.ipynb_checkpoints/` | Jupyter Notebook checkpoint files |

## Workflow

The notebook follows a typical end-to-end credit-risk machine learning workflow:

1. **Data loading** – Load the supplied credit and historical bureau datasets.
2. **Exploratory Data Analysis** – Inspect distributions, missing values, data types and relationships relevant to default risk.
3. **Data preprocessing** – Prepare numerical and categorical variables and handle data-quality issues.
4. **Feature preparation** – Combine and transform relevant applicant and historical-credit information.
5. **Model development** – Train classification models for predicting credit default risk.
6. **Evaluation** – Compare model predictions using appropriate classification metrics and examine model behaviour.
7. **Interpretation** – Use the analysis to understand which applicant/credit characteristics contribute to risk prediction.

## Dataset

The project uses data derived from the **Home Credit Default Risk** problem, which focuses on predicting whether a loan applicant will experience payment difficulties.

The repository includes compressed data files so that the analysis can be reproduced from the files stored here. Because the datasets are large, they may require substantial RAM and storage when extracted and loaded.

## Technologies

- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yuvraj619/Home_Credit_Default_Risk.git
cd Home_Credit_Default_Risk
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Extract the datasets

Unzip the required `.csv.zip` files into the project directory.

### 4. Run the notebook

```bash
jupyter notebook home_credit_default_risk.ipynb
```

Run the notebook cells from top to bottom to reproduce the analysis.

## Key Learning Objectives

- Understand credit-risk classification.
- Work with large, heterogeneous tabular datasets.
- Handle missing values and categorical variables.
- Perform exploratory analysis on financial data.
- Build and evaluate binary classification models.
- Understand the challenges created by class imbalance.
- Translate model outputs into practical credit-risk insights.

## Limitations

This repository is a machine learning project and should **not** be treated as a production credit-decision system. Financial decisions require additional validation, fairness analysis, regulatory review, monitoring, and domain-specific risk controls.

## Author

**Yuvraj Arora**  
GitHub: [@yuvraj619](https://github.com/yuvraj619)

---

If you find the project useful, feel free to explore the notebook and the other projects in the repository.