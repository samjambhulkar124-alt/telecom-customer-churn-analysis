# telecom-customer-churn-analysis
Telecom Customer Churn Analysis using Python, SQL, Exploratory Data Analysis, Data Visualization, and Machine Learning to understand customer churn patterns and evaluate churn prediction models.

# Telecom Customer Churn Analysis

## Project Overview

This project analyzes telecom customer data to understand customer churn patterns and explore whether machine learning can help identify customers who may leave the service.

The project uses Python, SQL, data visualization, and machine learning techniques to analyze customer information, compare churn patterns, and evaluate prediction models.

## Business Objectives

- Understand the percentage of customers who have churned.
- Explore churn patterns across different customer groups.
- Clean and prepare data for analysis.
- Build and compare machine learning models.
- Generate customer churn-risk scores and churn flags.
- Evaluate model performance and suggest business improvements.

## Tools and Technologies

- **Python** – Data analysis and machine learning
- **MySQL** – Data storage and data extraction
- **Jupyter Notebook** – Project development and documentation
- **Pandas and NumPy** – Data cleaning and manipulation
- **Matplotlib and Seaborn** – Data visualization
- **Scikit-learn** – Model training and evaluation
- **LightGBM** – Gradient boosting model

## Project Workflow

1. Connect to MySQL and load the telecom customer dataset.
2. Inspect the dataset, data types, missing values, and duplicate records.
3. Clean the data and prepare features for analysis.
4. Perform exploratory data analysis (EDA) using charts and graphs.
5. Prepare the target variable and split the data into training and testing sets.
6. Train and compare classification models.
7. Evaluate models using ROC-AUC and other classification metrics.
8. Perform cross-validation and model tuning.
9. Generate churn-risk scores and churn flags.
10. Summarize findings, limitations, and recommendations.

## Key Findings

- The dataset contains approximately 243,553 customer records.
- Approximately 20% of customers are labelled as churned.
- Initial model ROC-AUC scores are close to 0.50.
- Model tuning does not produce a meaningful improvement in churn prediction.
- Churn rates across the generated risk groups are similar, indicating that the current risk scores do not reliably identify high-risk customers.

## Business Recommendations

- Review the quality and relevance of the available customer features.
- Verify the churn target definition and investigate whether useful predictive information is missing.
- Explore additional customer behavior, service usage, complaints, and account history features where available.
- Collect more informative data before using churn-risk scores for business decisions.
- Re-evaluate model performance after improving the dataset and features.

## Conclusion

This project demonstrates the complete workflow of a customer churn analysis project, from SQL data extraction and data cleaning to visualization, model development, and evaluation.

The current models do not reliably distinguish customers who churn from those who stay. Further data investigation and feature improvement are required before the predictions can be considered useful for operational decision-making.

## Project File

- `No_Churn_Telecom_Submission_Ready.ipynb` – Jupyter Notebook containing the analysis, visualizations, machine learning workflow, and conclusion.

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries.
3. Configure access to your MySQL database.
4. Open the notebook in Jupyter Notebook.
5. Update the database connection settings using your own credentials.
6. Run the notebook cells from beginning to end.

## Author

**Data Analytics Portfolio Project**

*This project was created for learning and demonstrating practical data analytics and machine learning skills.*
