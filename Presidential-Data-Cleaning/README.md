📊 Excel Project: Presidential Data Cleaning & Preparation

Project Overview
This project focuses on cleaning and preparing a dataset containing information about U.S. presidents, their political parties, vice presidents, yearly salary, and timestamps.
The goal is to transform raw, inconsistent data into a clean, structured, analysis-ready dataset using Microsoft Excel.
Dataset Columns
The dataset contains the following fields:
S.No. – Serial number
president – President's name

party – Political party

vice – Vice president

salary – Annual salary

date updated – Last updated date

date created – Date record was created

🧹 Data Cleaning Tasks Performed
1️⃣ Removed Duplicates

Checked duplicates using S.No. and president fields

Ensured each president appears only once

2️⃣ Handled Missing Values

Checked for blank or missing fields

Replaced missing party/vice entries with "Unknown"

Ensured salary and date fields contain valid values

3️⃣ Standardized Text Formatting

Applied Excel formulas to clean and standardize text:

PROPER() → to fix inconsistent name capitalization

TRIM() → to remove extra spaces

Normalized party names (e.g., democrat → Democrat)

4️⃣ Corrected and Formatted Date Fields

Ensured consistent date formats using:

DATEVALUE()

Text to Columns → Date Conversion

Converted both:

date updated

date created
into standard YYYY-MM-DD format.

5️⃣ Cleaned Salary Field

Converted salary field to numeric values

Removed commas or text artifacts

Validated no negative or zero salary values

6️⃣ Added Derived Columns (Optional Enhancements)

To make the dataset more analytical:

Tenure_Days = date updated - date created

Salary_Category = (Low / Medium / High based on salary distribution)

Party_Code = Numeric mapping of political parties

📈 Final Output

After cleaning, the final dataset is:

Consistent

Accurate

Properly formatted

Ready for visualization or BI dashboards

📂 Project Structure
📁 Excel-Projects
   📁 Presidential-Data-Cleaning
       ├── Data Cleaning Excel Tutorial.xlsx
       ├── Cleaned_Data.xlsx
       ├── Screenshots/
       └── README.md

🧠 Skills Demonstrated

Data Cleaning

Data Transformation

Handling Missing Data

Standardizing Text

Date Formatting

Salary Validation

Creating Derived Columns

Preparing Data for Analysis

👤 Author

Rooshan Butt
Excel | SQL | Power BI | Data Analytics Portfolio
