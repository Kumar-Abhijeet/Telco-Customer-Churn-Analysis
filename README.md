# Telco Customer Churn Analysis

## Table of Contents
- [Overview](#overview)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Visual Insights](#visual-insights)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)
- [Repository Contents](#repository-contents)
- [How to Run the Project](#how-to-run-the-project)
- [Requirements](#requirements)
- [License](#license)

## Overview
[Customer churn](#overview) is a significant challenge faced by telecom companies. This project aims to identify the key factors influencing customer churn through data exploration and visualization techniques. By understanding why customers leave, telecom companies can devise effective retention strategies. This analysis uses a dataset of customer demographics, contract details, service usage, and payment methods to gain insights into customer behavior and identify churn patterns.

## Data Preprocessing
[Data Preprocessing](#data-preprocessing)
The dataset includes various types of customer information, such as demographics, service details, and payment methods. Before analysis, the following preprocessing steps were performed:

1. **Handling Missing Values**: Missing values in the `TotalCharges` column were replaced with zeros and converted to a float type for accurate analysis.
2. **Categorical Transformation**: The `SeniorCitizen` column, originally represented as numerical values (0 or 1), was transformed into categorical values ("Yes" or "No") for better interpretation.

## Exploratory Data Analysis (EDA)
[Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
Key findings from the exploratory data analysis include:

1. **Churn Rate**: Approximately 73.46% of customers have churned, highlighting the importance of understanding the factors driving this behavior.
2. **Demographics**: Senior citizens have a higher churn rate compared to non-senior customers, suggesting age may play a role in churn.
3. **Contract Type**: Customers with month-to-month contracts are more likely to churn than those with one-year or two-year contracts. Encouraging long-term contracts could help reduce churn.
4. **Internet Service Type**: Customers using fiber optic services have a higher churn rate compared to those using DSL. Service quality or pricing concerns may be influencing this trend.
5. **Payment Method**: Customers who use electronic checks have a higher churn rate compared to those using credit cards or bank transfers. This indicates that electronic checks may be less convenient or reliable.

## Visual Insights
[Visual Insights](#visual-insights)
Several charts and graphs were used to illustrate the findings:

- **Pie Chart**: Highlighted the overall proportion of customers who have churned.
- **Bar Charts**: Showed churn rates among different demographics, contract types, and payment methods.
- **Line Charts**: Examined trends in customer behavior over time.

## Recommendations
[Recommendations](#recommendations)
Based on the findings, the following recommendations are proposed to reduce customer churn:

1. **Encourage Long-Term Contracts**: Offer discounts or exclusive benefits to customers who switch from month-to-month to annual contracts.
2. **Improve Fiber Optic Service Quality**: Address issues related to fiber optic services, such as service quality and pricing, to improve customer satisfaction.
3. **Promote Convenient Payment Methods**: Introduce incentives for customers to use more reliable payment methods, such as credit cards or bank transfers.
4. **Targeted Customer Support**: Provide specialized support for high-risk groups, such as senior citizens and those on month-to-month contracts.

## Conclusion
[Conclusion](#conclusion)
This analysis identifies several key factors influencing customer churn, including contract type, payment method, and demographics. By implementing targeted retention strategies, telecom companies can reduce churn, improve customer satisfaction, and enhance overall financial performance.

## Repository Contents
[Repository Contents](#repository-contents)
- `TCA.ipynb`: Jupyter Notebook containing the data analysis and visualizations.
- `Customer Churn.csv`: Dataset used for the analysis.
- `Telco Customer Churn Analysis Report.pdf`: Detailed report summarizing the findings and recommendations.

## How to Run the Project
[How to Run the Project](#how-to-run-the-project)
1. Clone the repository.
2. Install the required dependencies using the command: `pip install -r requirements.txt`.
3. Open `TCA.ipynb` in Jupyter Notebook or any compatible environment to run the analysis.

## Requirements
[Requirements](#requirements)
- Python 3.x
- Jupyter Notebook
- Libraries: Pandas, Matplotlib, Seaborn, NumPy

## License
[License](#license)
This project is licensed under the MIT License.

