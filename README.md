# Titanic Dataset - Exploratory Data Analysis (EDA)

## Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns, relationships, and insights about passenger survival. The analysis includes data cleaning, univariate, bivariate, and multivariate analysis using Python's data science stack (Pandas, Matplotlib, and Seaborn).

## Dataset Information
The Titanic dataset contains information about 891 passengers aboard the RMS Titanic, including:
- Survival status (target variable)
- Passenger class
- Name, Sex, Age
- Number of siblings/spouses aboard (SibSp)
- Number of parents/children aboard (Parch)
- Ticket number
- Fare
- Cabin
- Port of Embarkation

Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

## Analysis Highlights

### Key Findings
1. **Class Impact**: 
   - 1st class passengers had 62% survival rate vs 24% for 3rd class
   - Higher classes had priority access to lifeboats

2. **Gender Bias**:
   - Female survival rate: 74%
   - Male survival rate: 19%
   - "Women and children first" policy evident

3. **Age Factor**:
   - Children (<10 years) had higher survival rates
   - 80% of children in 1st/2nd class survived

4. **Family Size**:
   - Passengers with 1-2 siblings/spouses had better survival odds
   - Large families (SibSp > 2) had lower survival rates

5. **Fare Correlation**:
   - Higher fare-paying passengers were more likely to survive
   - Median fare for survivors: £26 vs £10 for non-survivors

### Visualizations Included
- Histograms of numerical features
- Count plots of categorical features
- Survival rate by passenger class and gender
- Age distribution by survival status
- Correlation heatmap
- Pairplot of numerical features
- Violin plots showing age distribution by class and survival
- Scatter plots of fare vs age by survival

## Technical Implementation

### Dependencies
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

### Usage
1. Clone the repository:
   ```bash
   git clone [repository-url]
2. Install dependencies:
   ```bash
    pip install pandas matplotlib seaborn jupyter
3. Open and run the Jupyter Notebook:
   ```bash
    jupyter notebook Titanic_EDA.ipynb
