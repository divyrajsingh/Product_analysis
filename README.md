Amazon Electronics Sales Data Analysis

This project analyzes Amazon's electronics sales data to discover trends in user ratings, sales over time, and brand/category performance. The dataset contains over 1.29 million rows, providing extensive insights into user preferences and sales behavior across different electronics categories.


Dataset Source: Kaggle Electronics Dataset

Columns:
item_id: Unique identifier for each product.
user_id: Unique identifier for each user.
rating: User rating of the product (scale: 1 to 5).
timestamp: Date and time of the rating.
model_attr: User demographic attributes.
category: Electronics product category (e.g., Portable Audio & Video, Headphones).
brand: Brand of the product.
year: Year of the rating.
user_attr: Gender attribute of users.
split: Train/test split identifier.


Libraries Used
Pandas: For data manipulation and analysis.
NumPy: For numerical operations.
Matplotlib/Seaborn: For data visualization.


Data Cleaning

Converted data types for columns (timestamp, brand, category).
Handled missing values for brand and user_attr.
Removed duplicate rows and ensured no null ratings.


Key Insights

Best Year of Sales:

2015 had the highest sales in terms of total ratings.

Top Brands by Year:

In 2015: Bose was the most popular brand.
In 2018: Bose, Mpow, and Logitech were the top 3 brands.

Best Month of Sales:

January showed the highest number of sales across all years.


Category-wise Sales:

Top-selling category: Portable Audio & Video.
Least-selling category: Computers & Accessories.

Brand-wise Analysis:

Bose had the highest sales across the years, followed by Logitech and Etre Jeune.


Visualizations - 

Sales by Rating: Distribution of ratings across the dataset.

Sales by Year: Year-over-year performance, with 2015 showing peak activity.

Brand and Category Performance: Bar charts and pie charts illustrating the top-selling brands and categories.



Conclusion -

This analysis helps identify key trends in Amazon's electronics sales, with insights on top-performing brands, categories, and seasonal patterns. 

It can assist businesses in improving sales strategies by focusing on popular products and understanding customer preferences
