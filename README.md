# Elevate-labs-Task-1
🧹 Marketing Campaign Data Cleaning Project
This project focuses on cleaning a raw dataset named marketing_campaign_dirty.csv to prepare it for further analysis and visualization. The dataset contains information related to customer demographics and their response to a marketing campaign.

🗂️ Dataset Overview
The raw dataset contained:

Missing or null values

Duplicated rows

Inconsistent text formatting 

Unstandardized date formats

Improper column naming

Incorrect data types

✅ Cleaning Steps Performed
1. Handling Missing Values
Replaced all null or empty values with:

0 for numerical columns

"Unknown" for categorical columns

2. Removing Duplicates
Removed all duplicate rows to ensure data uniqueness and accuracy.

3. Text Standardization
Standardized text fields such as:
Education (e.g., graduation = Graduation)
Marital_Status  (e.g., Single and single = Single)

5. Date Format Conversion
Converted all date columns to a consistent format: dd-mm-yyyy

6. Renaming Columns
Renamed column headers to be:

Lowercase

Without spaces or special characters

Underscore-separated (e.g., Year Of Birth=Year_Of_Birth)

6. Fixing Data Types
Converted:

Age to int

Dates to datetime type

Other fields to appropriate data types

📁 Files Included
marketing_campaign_dirty.csv: Original dataset (raw)

marketing_campaign_cleaned.csv: Final cleaned dataset

🛠️ Tools Used
Advance excel

📊 Future Work
Perform Exploratory Data Analysis (EDA)

Build visualizations

Train machine learning models for marketing insights

