# Data-analysis-with-python
This Python project is focused on analyzing Diwali sales data to gain insights into customer demographics, purchase behavior, and sales trends.

This Python project is focused on analyzing Diwali sales data to gain insights into customer demographics, purchase behavior, and sales trends. The dataset contains records related to customer purchases, including details such as customer ID, gender, age, state, occupation, and the amount spent.

Tools and Libraries Used:
Pandas: Used for data loading, cleaning, and manipulation. It enables operations such as handling missing values and filtering data.

NumPy: Provides support for numerical operations, likely used alongside Pandas for data transformation.

Matplotlib and Seaborn: These libraries are employed for data visualization. Matplotlib offers basic plotting capabilities, while Seaborn provides more advanced, aesthetically pleasing visualizations.

Technical Work:
Data Loading and Inspection:

The dataset was loaded using pandas.read_csv(), with a special encoding (unicode_escape) to handle any non-ASCII characters.
A preview of the data (df.head()) showed relevant columns such as User_ID, Cust_name, Product_ID, Gender, Age Group, and more.
Data Cleaning:

The dataset initially had 15 columns, but two columns (Status and unnamed1) contained only null values and were dropped. Additionally, rows with missing values in the Amount column were removed to ensure accuracy.
After cleaning, the dataset had 11,239 rows and 13 columns.
Exploratory Data Analysis (EDA): Several insights were derived through exploratory data analysis using visualizations and groupings:

Gender-based Insights: A bar plot showed that the majority of customers are female, and females have a higher total purchasing amount compared to males.

Age Group Analysis: Most buyers fall in the 26-35 age group, indicating that this demographic is the primary consumer base during Diwali sales.

State-wise Sales: Uttar Pradesh, Maharashtra, and Karnataka were identified as the states with the highest number of orders and sales amounts.

Marital Status: A count plot and sales analysis revealed that married women tend to have a higher purchasing power, contributing significantly to the total sales.

Occupation Analysis: People working in the IT sector contributed the most to sales, followed by those in healthcare and aviation industries.

Product Category Sales: The highest sales volumes came from food, clothing, and electronics categories, indicating that these are the most popular product categories during the Diwali season.

Insights:
Female Dominance in Sales: The analysis shows that females, particularly those in the 26-35 age group, are the largest customer segment in terms of both the number of orders and total sales. This insight could help target marketing campaigns more effectively.

State and Regional Trends: Uttar Pradesh, Maharashtra, and Karnataka lead in both orders and sales volume, implying that regional promotions or offers could be particularly effective in these states during Diwali.

Occupation-based Targeting: Since customers in the IT sector have the highest purchase amounts, the company could consider launching targeted marketing strategies or special offers aimed at professionals in this field.

High-Value Product Categories: Food, clothing, and electronics products are the top-selling categories. Focusing promotions, discounts, and inventory management on these categories could maximize sales during future Diwali seasons.

Purchasing Power of Married Women: Married women have a higher purchasing power, likely due to household responsibilities during festivals. Marketing strategies and product offerings can be tailored to appeal to this demographic.

Conclusion:
This project successfully leveraged Python's data science libraries to provide a comprehensive analysis of Diwali sales data. By identifying key customer segments, geographic trends, and popular product categories, the insights gained from this project could significantly influence marketing strategies, inventory management, and sales optimization during festive seasons like Diwali.
