📋 Project Overview
This project analyzes a dataset of 1,000 customers to uncover the key factors driving bicycle purchases. By performing extensive data cleaning, constructing robust Pivot Tables, and designing an interactive Excel Dashboard, this project provides actionable insights into customer demographics, income levels, and commuting habits to help target marketing campaigns more effectively.

📊 Key Insights
The Sweet Spot: Middle-aged customers (35–54) represent the highest volume of bike buyers.

Income Matters: Customers who purchased bikes have a significantly higher average income than non-buyers across both genders.

Commute Factor: Interestingly, customers with short commutes (0–1 miles) are highly likely to buy bikes, while demand plummets for those commuting more than 5 miles.

🛠️ Data Processing Workflow
1. Data Cleaning & Transformation
Before building any visuals, the raw data was prepped using standard Excel techniques:

Duplicates: Removed 26 duplicate rows to ensure data integrity.

Marital Status & Gender: Used Find and Replace to change short codes (M/S and M/F) to full words (Married/Single and Male/Female) for better readability.

Income Formatting: Converted the income column to currency format and removed unnecessary decimals.

Age Brackets: Created a new Age Brackets column using a nested IF formula to segment customers into logical groups: =IF(A2>54, "Senior", IF(A2>=35, "Middle Age", "Young"))

🗂️ 2. Pivot Table Architecture
To extract specific metrics from the cleaned data, a series of tailored pivot tables were constructed to drive the dashboard visuals:

Income vs. Purchase: Aggregated the average income of buyers vs. non-buyers, segmented by gender.

Age Demographics: Tracked the count of bike purchases across the custom Young, Middle Age, and Senior brackets.

Commuter Dynamics: Isolated customer commute distances against their final purchase decisions to map geographic demand.

🖥️ 3. Completed Interactive Dashboard
The final phase involved synthesizing the pivot data into a centralized, user-facing dashboard sheet engineered for scannability and deep-dive analysis:

Visual Elements: Populated with Clustered Column Charts for demographic comparison and Line Graphs to illustrate the sharp decline in sales as commute length increases.

Interactive Slicers: Connected advanced slicers to all charts simultaneously, allowing stakeholders to filter the entire dashboard by Region, Education Level, and Occupation with a single click.

📁 Repository Structure
README.md - Project documentation

Data/raw_bike_data.csv - The original, uncleaned dataset

Bike_Sales_Dashboard.xlsx - The completed Excel workbook containing data, pivot tables, and dashboard tabs
