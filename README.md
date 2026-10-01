# Telecom Customer Churn & Usage Analysis

## Project Overview

This project analyzes telecom customer data to identify key patterns associated with customer churn. The analysis focuses on customer contract type, internet service, monthly charges, tenure, complaints, and customer service interactions to identify segments with higher churn risk.

## Project Objective

- Analyze overall customer churn and identify major churn patterns.
- Compare churn across different customer segments.
- Identify factors associated with higher customer churn.
- Generate actionable insights that can support customer retention strategies.

## Dataset

The dataset contains telecom customer information including:

- Contract type
- Internet service
- Tenure
- Monthly charges
- Payment method
- Customer service calls
- Number of complaints
- Churn status

## Tools & Technologies

- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Google Colab** – Development environment

## Project Structure

```text
Telecom-Customer-Churn-Analysis/
│
├── data/
│   └── Dataset
│
├── images/
│   ├── Churn by Contract Type.png
│   ├── Churn by Internet Service.png
│   └── Monthly Charges by Churn.png
│
├── notebooks/
│   └── Telecom_Customer_Churn_&_Usage_Analysis.ipynb
│
└── README.md

```

## Methodology

1. Loaded and inspected the telecom customer dataset.
2. Checked data quality and prepared the data for analysis.
3. Analyzed customer churn across key customer attributes.
4. Compared churn rates across different segments.
5. Created visualizations to identify significant patterns.
6. Interpreted the findings from a business perspective.
7. Derived recommendations based on the observed churn patterns.

## Key Findings

### 1. Overall Churn

The analysis found that **33.88% of customers had churned**, while **66.12% remained with the company**.

This indicates a significant level of customer attrition and highlights the need to identify high-risk customer segments.

### 2. Churn by Contract Type

Contract type showed a strong difference in churn:

- **Month-to-Month:** 53.91%
- **One Year:** 17.02%
- **Two Year:** 2.52%

Month-to-month customers had substantially higher churn compared with customers on longer-term contracts.

[Churn by Contract Type](images/Churn%20by%20Contract%20Type.png)

**Business Insight:** Customers without long-term commitments represent a higher-risk segment and can be considered for targeted retention initiatives.

### 3. Churn by Internet Service

Churn rates varied across internet service categories:

- **Fiber Optic:** 39.66%
- **DSL:** 28.78%
- **No Internet:** 29.57%

[Churn by Internet Service](images/Churn%20by%20Internet%20Service.png)

**Business Insight:** Internet service type shows noticeable differences in customer churn and can be used as an important segmentation variable when analyzing customer retention.

### 4. Monthly Charges by Churn

Customers who churned had a higher average monthly charge:

| Customer Status | Average Monthly Charges |
| --------------- | ----------------------- |
| Stayed          | 652.28                  |
| Churned         | 705.78                  |

[Monthly Charges by Churn](images/Monthly%20Charges%20by%20Churn.png)

**Business Insight:** Higher-paying customers showed greater churn in this dataset, making pricing and customer value important areas to consider when developing retention strategies.

### 5. Complaints and Churn

The analysis also showed a strong increase in churn as the number of customer complaints increased.

- **0 complaints:** 24.64% churn
- **3 complaints:** 68.00% churn

**Business Insight:** Customers with repeated complaints represent a higher-risk segment, highlighting the importance of resolving service issues before dissatisfaction leads to churn.

## Business Recommendations

Based on the analysis:

- Develop targeted retention strategies for **month-to-month customers**.
- Investigate the reasons behind higher churn among **fiber-optic customers**.
- Monitor customers with **higher monthly charges** for potential dissatisfaction or pricing concerns.
- Prioritize customers with **multiple complaints** for proactive support and issue resolution.
- Use customer segmentation to identify high-risk groups before they churn.

## How to Run

### 1. Clone the Repository

```bash
git clone <repository-url>

```

### 2. Open the Notebook

Open the notebook from the `notebooks/` folder using **Google Colab** or **Jupyter Notebook**.

### 3. Verify the Dataset

Make sure the dataset is available in the `data/` folder and update the file path in the notebook if required.

### 4. Run the Analysis

Run the notebook cells sequentially to reproduce the data cleaning, analysis, visualizations, and findings.

## Conclusion

The analysis identified clear differences in customer churn across contract type, internet service, monthly charges, and complaint frequency. Month-to-month customers and customers with repeated complaints showed particularly high churn rates.

These findings demonstrate how exploratory data analysis and visualization can be used to identify high-risk customer segments and support data-driven customer retention strategies.

## Future Scope

- Develop a **machine learning model** to predict individual customer churn probability.
- Build an **interactive Power BI dashboard** for ongoing churn monitoring.
- Analyze **customer lifetime value (CLV)** alongside churn risk.
- Develop a customer-level **churn risk segmentation** framework.

## Project Skills Demonstrated

**Data Cleaning • Exploratory Data Analysis • Customer Segmentation • Data Visualization • Business Insights • Python • Pandas • NumPy • Matplotlib • Seaborn**

Now this ChatGPT fucker gave me this professional version 2 update in the mefo section. Earlier it was not as professional according to that. So now what do I need to do? Like I have to edit the whole thing? And also it says, it says, Check your notebook file path that exactly matches the name files in your image folder. I don't know what the fuck is this. How would I do this now? This is so... I mean Google gave it in one go. Why don't do that?
