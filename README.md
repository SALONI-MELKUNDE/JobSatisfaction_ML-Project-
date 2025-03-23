
# Employee Job Satisfaction Prediction: Sweden vs. Germany

A machine learning project analyzing and predicting job satisfaction using survey data from Sweden and Germany. Includes data cleaning, exploratory analysis, feature engineering, and implementation of various ML models with performance comparison.

## Table of Contents 👁️📌
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [License](#license)

---

## Project Overview 🌐

This project compares employee job satisfaction between Sweden and Germany using survey data analysis and predictive modeling. Key components:

- Data filtering and cleaning
- Exploratory Data Analysis (EDA)
- Correlation analysis
- Principal Component Analysis (PCA)
- Multiple machine learning models:
  - Logistic Regression
  - Decision Trees
  - SVM
  - Naive Bayes
  - K-Nearest Neighbors
  - Random Forest
  - Gradient Boosting
  - XGBoost
- Model performance comparison
- Feature importance analysis

---

## Features

- **Data Preprocessing**:
  - Handling missing values
  - Data type conversion
  - Country-specific filtering
  - Median imputation
  
- **Visualization**:
  - Distribution plots
  - Correlation heatmaps
  - PCA visualizations
  - Confusion matrices
  - Feature importance charts

- **Modeling**:
  - Hyperparameter tuning with GridSearchCV
  - Cross-validation
  - Performance metrics tracking
  - Comparative analysis between countries

---

## Installation

**1. Clone repository:**

```bash
git clone https://github.com/SALONI-MELKUNDE/JobSatisfaction_MLProject.git
cd JobSatisfaction_MLProject
```

**2. install requirements files:**

- pandas==1.5.3
- numpy==1.24.3
- scikit-learn==1.2.2
- matplotlib==3.7.1
- plotly==5.14.1
- xgboost==1.7.6
- ipython==8.12.0

## Usage

**1. This will execute:**
- Data preprocessing
- EDA visualizations
- PCA transformation
- Model training/evaluation
- Performance metric generation

**2. Outputs will be saved in:**
- cleaned_datasets/ (processed data)
- results/ (visualizations and metrics)
- models/ (saved model weights)


## Dataset

- **Processed datasets include:** 
  - Country-specific filtered data
  - PCA-transformed versions (4 components)
  - Cleaned datasets with median imputation
 
## Results

- Workplace relations showed highest correlation with job satisfaction
- Random Forest and XGBoost achieved best performance
- Sweden models generally outperformed Germany counterparts
- PCA helped improve model interpretability

## License 📜

- **This project is licensed under the MIT License.
(Include or reference the actual LICENSE file in my repository.)**

  
## Thank you for exploring the Jobsatisfaction_MLProject! 🎉

- **If you have any questions or suggestions, feel free to open an issue or reach out.** 💬 📬


