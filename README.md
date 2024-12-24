# Insurance-Claims
Key Actions Performed

Combined two datasets (claims data and customer demographics) into a unified dataset with 1,107 records and 15 attributes.
Imputed missing values using the mean for numerical data and mode for categorical data.
Converted claim_amount from string to numeric by removing the $ sign.
Data Preparation and Transformation:

Created new flags for unreported claims (police reports missing).
Retained the latest claim for customers with duplicate entries.
Categorized customers into age groups: Children (<18), Youth (18–30), Adults (30–60), and Seniors (>60).
Exploratory Data Analysis (EDA):

Average claim amounts by customer segment:
Platinum: $12,370
Gold: $12,755
Silver: $12,271
Total claim amounts based on incident causes:
Crime: $724,463
Driver Error: $3.26 million
Monthly claim trends revealed the highest total claims in July ($1.37 million).
Fraud Analysis:

Adults accounted for the most fraudulent claims (758 cases).
Created bar charts to compare fraudulent activities by gender and age group.
Insights from Claims and Customers:

Gender-based spending:
Males: Average claim amount $71,367
Females: Average claim amount $63,778
Customers from TX, DE, and AK with driver-related issues made 35 claims.
Statistical Analysis and Hypothesis Testing:

Found no significant difference in claim amounts between males and females (p-value = 0.186).
Determined no relationship between age groups and customer segments.
Verified a significant increase in 2018 claim amounts compared to the fiscal average of $10,000 (p-value < 0.05).
Visualizations:

Pie charts for gender-segment claim amounts.
Line charts for monthly trends in claim amounts.
Quantitative Highlights:

Processed 1,107 records with 15 attributes.
Average adult claim amount: $12,807.
Identified fraudulent claims in 68% of adults' cases.
Maximum claim category: "Driver Error" incidents at $3.26 million.
Technologies Used:

Python (Pandas, NumPy, Seaborn, Matplotlib) for data processing and visualization.
Scipy for statistical hypothesis testing.
