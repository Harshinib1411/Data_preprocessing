#Data_preprocessing

Data Cleaning using Power Query – Excel
This project showcases a complete data preprocessing workflow using Power Query Editor (Microsoft Excel). The original dataset contained several common real-world data quality issues which were systematically cleaned and transformed to create a consistent, analysis-ready version.

🔧 Cleaning & Pre-Processing Tasks Performed
Task	Description
Duplicate Removal	Identified and removed exact duplicate rows from the dataset
Null Handling	Replaced missing values in important numerical columns (e.g., Amount) using median imputation to avoid skew and maintain data integrity
Date Standardization	Converted multiple inconsistent date formats into a single uniform format
Text Formatting	Cleaned text columns by:
– Removing extra spaces
– Applying proper capitalization across all categorical fields (e.g., names, categories) to ensure consistency
Outlier / Irregular Value Treatment	Standardized irregular numeric entries and ensured all values fall within logical ranges
Data Type Changes	Converted columns to appropriate data types (dates, numbers, text) for accurate downstream analysis

⚙️ Tools Used
Microsoft Excel (Power Query Editor)

M-Language (Power Query Formula Language) (internally used)

📁 Output
The cleaned dataset is exported back to Excel as a new worksheet/table and is ready for:

Exploratory Data Analysis (EDA)

Dashboards (Power BI / Excel)
