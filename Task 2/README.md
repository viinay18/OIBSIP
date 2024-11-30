Project Title: Data Cleaning and Analysis of Istanbul Shopping Mall Dataset (2021–2023)

Description: 
This project focuses on cleaning the Istanbul shopping mall dataset, addressing issues like missing data, duplicates, and inconsistencies to ensure a reliable dataset. The analysis covers customer demographics, payment methods, product categories, and shopping trends.

Dataset Overview 
Source : Istanbul Shopping Mall Sales Data (2021–2023)
Structure : Includes customer demographics (age, gender), transaction details (invoice numbers, prices, quantities), payment methods, product categories, and shopping mall locations.

Detailed Key Steps:
1) Exploratory Data Analysis (EDA):
Inspected key columns (age, price, quantity, payment method) to identify potential issues.
Used statistical summaries (mean, median, mode) and visualizations (histograms, boxplots) to uncover trends and detect anomalies, such as unusual prices or missing values.

2) Handling Missing Values:
Checked for missing data and applied imputation for numeric values (e.g., age, quantity).
Removed rows with excessive missing or irrelevant data.
Standardized inconsistent entries in the payment_method column.

3) Duplicate Records Removal:
Removed duplicate transactions based on invoice_no and customer_id to ensure data accuracy.

4) Standardization and Formatting:
Standardized columns (e.g., price, quantity, payment_method) and ensured proper data types for numerical and categorical fields.

5) Outlier Detection and Treatment:
Identified outliers using boxplots and histograms for price and quantity.
Applied z-scores and IQR methods to handle outliers by capping or excluding extreme values.

6) Data Validation:
Conducted post-cleaning validation to ensure data integrity, verifying critical fields (e.g., invoice_no, customer_id, price), ensuring no erroneous records remained.

Outcome:
A cleaned, standardized dataset ready for analysis, providing insights into shopping trends, customer behavior, and purchasing patterns across Istanbul’s malls. This prepares the dataset for actionable recommendations and decision-making in retail management.


