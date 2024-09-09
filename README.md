# Diwali Sales Data Analysis

This **Python project** focuses on analyzing **Diwali sales data** to gain insights into customer demographics, purchase behavior, and sales trends. The dataset contains records related to customer purchases, including details such as customer ID, gender, age, state, occupation, and the amount spent.

## Tools and Libraries Used

- **Pandas**: Used for data loading, cleaning, and manipulation, enabling operations such as handling missing values and filtering data.
- **NumPy**: Supports numerical operations alongside Pandas for data transformation.
- **Matplotlib and Seaborn**: Employed for data visualization. Matplotlib offers basic plotting capabilities, while Seaborn provides more advanced, aesthetically pleasing visualizations.

## Technical Work

### Data Loading and Inspection

The dataset was loaded using `pandas.read_csv()`, with special encoding (`unicode_escape`) to handle any non-ASCII characters. A preview of the data (`df.head()`) showed relevant columns such as `User_ID`, `Cust_name`, `Product_ID`, `Gender`, `Age Group`, and more.

### Data Cleaning

The dataset initially had 15 columns, but two columns (`Status` and `unnamed1`) contained only null values and were dropped. Additionally, rows with missing values in the `Amount` column were removed to ensure accuracy. After cleaning, the dataset had **11,239 rows and 13 columns**.

## Exploratory Data Analysis (EDA)

Several insights were derived through exploratory data analysis using visualizations and groupings:

- **Gender-based Insights**: A bar plot showed that the majority of customers are **female**, and females have a higher total purchasing amount compared to males.
- **Age Group Analysis**: Most buyers fall in the **26-35 age group**, indicating that this demographic is the primary consumer base during Diwali sales.
- **State-wise Sales**: Uttar Pradesh, Maharashtra, and Karnataka were identified as the states with the highest number of orders and sales amounts.
- **Marital Status**: Analysis revealed that **married women** tend to have higher purchasing power, contributing significantly to total sales.
- **Occupation Analysis**: People working in the **IT sector** contributed the most to sales, followed by those in healthcare and aviation industries.
- **Product Category Sales**: The highest sales volumes came from **food, clothing, and electronics** categories.

## Insights

- **Female Dominance in Sales**: Females, particularly in the **26-35 age group**, are the largest customer segment in terms of both the number of orders and total sales. This insight can help target marketing campaigns more effectively.
  
- **State and Regional Trends**: Uttar Pradesh, Maharashtra, and Karnataka lead in both orders and sales volume, implying that **regional promotions** or offers could be particularly effective in these states during Diwali.

- **Occupation-based Targeting**: Customers in the **IT sector** have the highest purchase amounts, suggesting that the company could launch targeted marketing strategies aimed at professionals in this field.

- **High-Value Product Categories**: Focusing on **food, clothing, and electronics** for promotions, discounts, and inventory management could maximize sales during future Diwali seasons.

- **Purchasing Power of Married Women**: Married women, especially during festivals, have higher purchasing power. Marketing strategies and product offerings can be tailored to this demographic.

## Conclusion

This project successfully leveraged Python's data science libraries to provide a comprehensive analysis of Diwali sales data. By identifying key customer segments, geographic trends, and popular product categories, the insights gained from this project could significantly influence **marketing strategies**, **inventory management**, and **sales optimization** during festive seasons like Diwali.
