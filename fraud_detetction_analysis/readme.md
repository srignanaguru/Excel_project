# Fraud Detection Analysis Using Excel and Power Query

## 1. Data Retrieval and Transformation
Downloaded the fraud detection dataset from Kaggle. The dataset was in a text file format (comma-separated values).
Transformed the text file into a CSV format using a Python script (fraud_detection.ipynb).

## 2. Data Cleaning and Preprocessing in Power Query
Performed data cleanup and transformation using Power Query:

**Filtered Null Values** – Removed missing or incomplete data.

**Removed Empty Columns** – Eliminated columns with no meaningful data.

**Deleted Unnecessary Columns** – Optimized file size and improved performance by removing irrelevant attributes.

Loaded the cleaned dataset into Excel for further processing and analysis.

## 3. Fraud Detection Criteria
Identified fraudulent activities based on the following three key indicators:

**Over Limit Transaction** – Spending over the credit card limit.

**Mismatched CVV** – The registered card CVV does not match the transaction CVV, indicating possible fraud.

**Low Available Balance After Transaction** – Transactions occur even when the available balance is critically low.

Created a separate column in Excel to track these fraud indicators and analyze anomalies.

## 4. Fraudster Categorization
Classified fraudsters based on their fraudulent activities:

**Occasional Fraudster** – Engaged in one fraud activity.

**Repeat Offender** – Engaged in two fraud activities.

**Serial Fraudster** – Engaged in all three fraud activities.

Additionally, identified non-fraudulent accounts and labeled them as "Not Fraud" in the dataset.

## 5. Data Visualization & Insights
Utilized Excel charts and pivot tables for fraud analysis:

**Pie Chart with Slicer**
Categorized accounts into:

- Not Fraudulent

- Occasional Fraudster

- Repeat Offender

- Serial Fraudster

Used a slicer for dynamic selection of fraud categories.

**Top 10 Fraudsters Bar Chart**
Displayed account numbers with the highest fraud activity count.

**Over Limit Transactions Analysis**
Bar chart showing the sum of Credit Limit and Transaction Amount, categorized by fraud status (Fraud/OK).

Successfully identified fraudulent transactions based on defined criteria.
Categorized fraudsters into different levels based on activity patterns.
Visualized fraud trends using Excel’s Power Query and charts.
