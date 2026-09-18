# Dirty_cafe_python_analysis
Project overview
This project performs an end-to-end Cafe Sales Analysis using Python. The objective is to clean and analyze cafe transaction data, identify sales patterns, understand customer purchasing behavior, and generate meaningful business insights.

The project includes data cleaning, exploratory data analysis (EDA), feature engineering, data visualization, business analysis

 Dataset

The dataset contains cafe transaction-level information.

Main Columns

Column	Description
Transaction ID	Unique transaction identifier
Item	Product purchased
Quantity	Number of items purchased
Price Per Unit	Price of one item
Total Spent	Total transaction amount
Payment Method	Payment method used
Location	Cafe/store location
Transaction Date	Date of transaction

Technologies Used

* Python
* Pandas — Data manipulation and analysis
* NumPy — Numerical operations
* Matplotlib — Data visualization
* Seaborn — Statistical visualization
* Jupyter Notebook — Data analysis
1. Data Cleaning

The raw dataset was inspected and cleaned before performing analysis.

Cleaning activities included:

* Handling missing values
* Handling invalid values such as ERROR and UNKNOWN
* Converting numerical columns to appropriate data types
* Converting transaction date into datetime format
* Checking duplicate records
* Checking inconsistent categorical values
* Validating calculated transaction amounts
* Removing or handling invalid records

🔍 2. Exploratory Data Analysis

The dataset was analyzed using Pandas, Matplotlib, and Seaborn.
Analysis performed:
* Dataset shape and structure
* Data types
* Missing-value analysis
* Duplicate analysis
* Descriptive statistics
* Product analysis
* Payment-method analysis
* Location analysis
* Time-based analysis
* Revenue analysis
* Transaction analysis
* Correlation analysis
3. Feature Engineering
Year
Month
Month_Name
Day
Day_Name
Week
Revenue_Per_Item
Transaction_Category
4. Data Visualization


* Revenue by Product
*  Quantity Sold by Product
*  Revenue by Payment Method
* Revenue by Location
* Monthly Revenue Trend
*  Revenue by Day of Week
* Payment Method Distribution
*  Product vs Location Heatmap
* Transaction Amount Distribution
* Correlation Heatmap
* Average Transaction Value
The analysis focuses on identifying insights such as:

* Top-performing products
* High-revenue locations
* Preferred payment methods
* Monthly sales trends
* Weekday vs weekend performance
* Customer transaction behavior
* Revenue contribution by product
* High-value transactions

3. Run the Jupyter Notebook

Open VS Code or Jupyter Notebook and open:

Notebook/Cafe_Sales_Analysis.ipynb

Run the notebook cells from top to bottom.

The notebook performs:

Data Loading
→ Cleaning
→ EDA
→ Feature Engineering
→ Visualization
→ Business Questions
→ Insights



👨‍💻 Author

Abhishek Ghoter

BCA | Aspiring Data Analyst / Data Scientist

Connect With Me

* LinkedIn:www.linkedin.com/in/abhishek-ghoter-69a987310
* Gmail: abhishekghoter1@gmail.com
