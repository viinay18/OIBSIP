Project Title: Comprehensive Data Cleaning of NYC Airbnb Dataset (2019)

Description:
The project entails cleaning and preparing the NYC Airbnb Open Data (2019) for high-quality analysis. It focuses on identifying and resolving issues such as missing data, duplicates, inconsistent formatting, and outliers to ensure an accurate, consistent, and reliable dataset.

Dataset Overview:
Source: NYC Airbnb Open Data (2019).
Structure: Includes host information, property details, geographical locations, pricing, availability, and reviews.

Detailed Key Steps:
1) Exploratory Data Analysis (EDA):
  Initial inspection of the dataset to identify key issues.
  Used statistical summaries to highlight anomalies in columns like price, availability_365, and minimum_nights.

2) Handling Missing Values:
  Conducted column-wise checks for missing data.
  Applied conditional imputation for numeric fields such as reviews_per_month.
  Dropped irrelevant rows with excessive missing data, preserving data quality.

3) Duplicate Records Removal:
  Detected duplicate rows using the id column.
  Ensured that unique listings were retained to avoid bias in analysis.

4) Standardization and Formatting:
  Normalized key columns (price, availability_365, etc.) to maintain consistency.
  Ensured proper data types for numerical and categorical variables.
  Uniform formatting of text columns like neighbourhood_group and room_type.

5) Outlier Detection and Treatment:
  Identified outliers using visualization tools like boxplots and histograms.
  Applied z-score and IQR methods to detect and treat extreme values in critical columns such as price and minimum_nights.
  Outliers were either capped, replaced, or excluded based on their potential impact.

6) Data Validation:
  Post-cleaning checks ensured the integrity and usability of the dataset.
  Verified that no erroneous data persisted, particularly in critical columns.

Outcome:
A thoroughly cleaned and standardized dataset ready for analysis, ensuring reliable insights into NYC Airbnb trends and patterns. This work creates a foundation for robust decision-making in data-driven projects.
