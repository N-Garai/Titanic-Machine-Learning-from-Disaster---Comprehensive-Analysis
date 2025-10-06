# Titanic: Machine Learning from Disaster - Comprehensive Analysis 🚢

## Project Overview

This project presents a comprehensive analysis of the famous Titanic dataset, exploring survival patterns and building predictive models to understand the factors that influenced passenger survival during the Titanic disaster.

**Live Analysis Report: [View on RPubs](https://rpubs.com/N-Garai/1351991)**

## Key Features

- 📊 Detailed exploratory data analysis
- 🔍 Advanced data visualization
- ⚙️ Feature engineering
- 🧪 Multiple machine learning models
- 📈 Model comparison and evaluation

## Data Analysis

### Exploratory Data Analysis (EDA)

- **Demographics Analysis**: In-depth analysis of passenger characteristics
- **Survival Patterns**: Comprehensive study of survival rates across different factors
- **Missing Data**: Systematic handling of missing values using advanced imputation techniques

### Key Insights

1. **Gender Impact**:
   - Female passengers had a significantly higher survival rate (74.2%)
   - Male passengers had a much lower survival rate (18.9%)

2. **Class Analysis**:
   - 1st Class: 62.96% survival rate
   - 2nd Class: 47.28% survival rate
   - 3rd Class: 24.24% survival rate

3. **Family Size Impact**:
   - Small families (2-4 members) had better survival rates
   - Solo travelers and large families had lower survival rates

4. **Age Factors**:
   - Children had higher survival rates
   - Different age groups showed varying survival patterns across classes

## Machine Learning Models

### Models Implemented

1. **Logistic Regression**
2. **Random Forest**
3. **XGBoost**
4. **Support Vector Machine (SVM)**

### Model Performance

Model | Accuracy | Sensitivity | Specificity | F1 Score
------|----------|-------------|-------------|----------
Logistic Regression | 0.8268 | 0.7711 | 0.8627 | 0.7816
Random Forest | 0.8324 | 0.7831 | 0.8627 | 0.7917
XGBoost | 0.8268 | 0.7711 | 0.8627 | 0.7816
SVM | 0.8268 | 0.7711 | 0.8627 | 0.7816

### Feature Importance

Key predictive features identified:
- Sex
- Title (extracted from name)
- Fare
- Age
- Passenger Class
- Family Size

## Feature Engineering

Several derived features were created to improve model performance:
- Title extraction from names
- Family size categories
- Fare per person
- Deck information from cabin
- Age groups
- Child indicator
- Mother indicator

## Technical Implementation

### Tools & Libraries Used

- **R Programming Language**
- **Key Libraries**:
  - tidyverse (data manipulation)
  - caret (machine learning)
  - randomForest
  - xgboost
  - e1071 (SVM)
  - ggplot2 (visualization)

### Advanced Visualizations

- Correlation heatmaps
- Survival probability curves
- Age pyramids
- Interactive survival matrices
- Distribution plots

## Conclusions

The analysis reveals that survival on the Titanic was significantly influenced by:
1. Social status (passenger class)
2. Gender
3. Age
4. Family structure

The best performing model (Random Forest) achieved an accuracy of 83.24% in predicting survival.

## How to Use

1. Clone this repository
2. Install required R packages
3. Run the R Markdown file
4. View the generated analysis report

## Credits

Created by: N-Garai
Dataset: [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)

## License

This project is open source and available under the [MIT License](LICENSE)
