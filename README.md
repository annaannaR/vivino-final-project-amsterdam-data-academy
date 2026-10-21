# Vivino Wine Data Analysis & Machine Learning

### Final Data Science Project | Amsterdam Data Academy

## Project Overview

This project was developed as part of the **Amsterdam Data Academy Data Science program**.

The main objective was to analyze wine data from Vivino, identify factors influencing wine ratings, compare producers and regions, and apply machine learning techniques to predict wine ratings.

The project also explores whether higher wine prices correspond to better ratings and identifies highly rated wines that offer good value for money.

## Technologies & Libraries

- **Python** – Data processing and analysis
- **Pandas & NumPy** – Data cleaning and manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine learning and preprocessing
- **Jupyter Notebook / Google Colab** – Development environment

## Project Workflow

### 1. Data Cleaning & Preparation

- Imported wine data from Excel.
- Combined data from multiple sheets.
- Cleaned and standardized text values.
- Extracted vintage years from wine names.
- Identified non-vintage wines.
- Prepared the dataset for statistical analysis and modeling.

### 2. Exploratory Data Analysis (EDA)

Analyzed relationships between:

- Wine ratings and prices
- Wine producers and average ratings
- Wine regions and ratings
- Number of reviews and wine ratings
- Vintage years and wine ratings

Explored wine characteristics and identified patterns using statistical analysis and visualizations.

### 3. Wine Producer & Region Ranking

Developed a weighted scoring approach to compare wine producers and regions based on their ratings.

Grouped wines into price categories to identify highly rated options across different price ranges.

The analysis considered both ratings and prices to support value-for-money comparisons.

### 4. Feature Engineering

Applied several preprocessing techniques:

- Target encoding for categorical features
- Logarithmic transformations of prices and review counts
- Creation of vintage-related features
- Correlation analysis
- Training and testing data splits

### 5. Machine Learning

Implemented and compared regression models to predict wine ratings:

**Linear Regression**
- Investigated relationships between wine characteristics and ratings.
- Examined the influence of producers, regions, prices, and vintage years.

**Decision Tree Regression**
- Trained models with different maximum tree depths.
- Analyzed feature importance.
- Evaluated predictive performance.

Model performance was assessed using **Mean Squared Error (MSE)**.

## Key Findings

- Wine ratings were strongly associated with producer reputation and historical ratings.
- Higher prices did not consistently correspond to higher ratings.
- Luxury wines showed a stronger relationship between price and rating.
- Producer-related features played an important role in predicting wine ratings.
- Wine selection based on ratings, popularity, and price can help identify better-value options.

## Wine Selection Criteria

The final analysis identified wines meeting the following conditions:

- Average rating of at least **4.2**
- At least **100 reviews**
- Price below the dataset's median price

These criteria were used to identify highly rated wines at relatively affordable prices.

## Project Outcomes

This project demonstrates practical experience in:

- Data Cleaning & Preparation
- Exploratory Data Analysis
- Statistical Analysis
- Data Visualization
- Feature Engineering
- Predictive Modeling
- Machine Learning Model Evaluation
- Data-Driven Decision Making

## Author

**Anna Rogiewicz ** - LinkedIn Profile

Data Science | Data Analytics | Python | SQL | Power BI

Amsterdam Data Academy – Final Project
