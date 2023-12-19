# Marketing Analytics Project: Predictive Customer Spend Analysis

## Project Overview

This project focuses on developing a comprehensive predictive model to estimate future customer spending based on historical behavior. Utilizing data from an online-only gift retail shop, the analysis spans two years of customer transactions. The primary objective is to enable optimized marketing strategies and enhance strategic decision-making through in-depth data analysis and modeling.

## Data Description

The dataset encompasses two years of transaction records from an online gift retail shop. It includes detailed customer purchase history, product information, and transaction timestamps. The data is sourced from two CSV files, representing the years 2009-2010 and 2010-2011, which are then merged for a holistic analysis.

## Analytical Approaches and Models

The project employs various analytical techniques and predictive models, outlined as follows:

### Exploratory Data Analysis (EDA)
- **Monthly Sales Trends**: Analysis of sales patterns over months to identify trends and seasonality.
- **Top 10 Products**: Identification of the most popular products based on sales data.
- **Number of Transactions**: Examination of transaction volumes over time.

### RFM (Recency, Frequency, Monetary) Model
- **Customer Segmentation**: Segmenting customers based on RFM values to identify high-value customers and tailor marketing strategies accordingly.

### Trend Analysis
- **Unique Customers**: Tracking the number of unique customers over time.
- **Total Purchases and Total Revenue**: Analyzing overall purchases and revenue trends.

### Time Series Analysis
- Comprehensive analysis of time-related trends in customer purchasing behavior.

### Predictive Modeling
- **BG/NBD Model**: Employing the Beta-Geometric/Negative Binomial Distribution model to predict expected future purchases and sales.
- **CLV Prediction**: Utilizing the Gamma-Gamma model, Pareto/NBD, and Modified BG/NBD for predicting customer lifetime value.

## Results and Conclusions

The project yields critical insights into customer buying patterns, product popularity, and sales trends. The predictive models provide robust forecasts of future customer spending, enabling the formulation of targeted marketing strategies and informed business decisions. Key findings are detailed in the project's markdown files.

## Libraries and Tools Used

- **Data Manipulation and Analysis**: Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn, Plotly
- **Machine Learning and Predictive Modeling**: Scikit-learn, XGBoost
- **Customer Lifetime Value Analysis**: Lifetimes package

## Running the Notebook

To execute the notebook:
1. Ensure Python is installed on your system.
2. Install necessary libraries using `pip`:
   ```
   pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost lifetimes
   ```
3. Load the Jupyter Notebook and run each cell sequentially.

Note: The notebook contains a mix of code and markdown cells for a comprehensive understanding of the analysis.

---
