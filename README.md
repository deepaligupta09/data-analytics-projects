# Telecom Customer Churn & Usage Analysis

## Project Objective

Analyze telecom customer data to identify key patterns associated with customer churn and understand which customer segments are more likely to leave.

## Dataset

The dataset contains telecom customer information including contract type, internet service, tenure, monthly charges, complaints, customer service calls, payment method, and churn status.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Project Structure

- `data/` – Dataset used for analysis
- `notebooks/` – Complete Python analysis notebook
- `images/` – Key analysis visuals
- `README.md` – Project documentation

## Methodology

1. Loaded and inspected the dataset
2. Checked data quality and prepared the data
3. Analyzed churn across different customer segments
4. Created visualizations to identify important patterns
5. Interpreted findings from a business perspective

## Key Analysis & Insights

### Churn by Contract Type

Month-to-month customers showed the highest churn rate, while customers with longer-term contracts showed substantially lower churn.

![Churn by Contract Type](images/Churn%20by%20Contract%20Type.png)

### Churn by Internet Service

Customers using different internet services showed noticeable differences in churn rates, highlighting internet service type as an important segment for analysis.

![Churn by Internet Service](images/Churn%20by%20Internet%20Service.png)

### Monthly Charges by Churn

Customers who churned had higher average monthly charges compared with customers who stayed.

![Monthly Charges by Churn](images/Monthly%20Charges%20by%20Churn.png)

## How to Run

1. Clone this repository.
2. Open the notebook from the `notebooks/` folder in Google Colab or Jupyter Notebook.
3. Make sure the dataset is available in the `data/` folder.
4. Run the notebook cells sequentially.

## Conclusion

The analysis identified clear differences in churn across contract type, internet service, and monthly charges. These patterns can help identify higher-risk customer segments and support targeted customer retention strategies.

## Future Scope

- Build a machine-learning model to predict customer churn.
- Create an interactive Power BI dashboard for churn monitoring.
- Analyze customer lifetime value alongside churn risk.
