# Innomatics_Research_Labs_Advanced-GenAI-Internship_Entrance_Test
Technical Evaluation (Online Hackathon) i for participants pursuing eligibility for the Advanced Generative AI Internship Program

This project focuses on analyzing food delivery data to uncover insights into order trends, user behavior, restaurant performance, and revenue distribution. The analysis combines data from three distinct sources: orders.csv, users.json, and restaurants.sql.

## Data Sources
**orders.csv**: Contains details about individual food orders, including order_id, user_id, restaurant_id, order_date, total_amount, and restaurant_name.

**users.json**: Provides user-specific information such as user_id, name, city, and membership status.

**restaurants.sql**: A SQL database containing restaurant details, including restaurant_id, restaurant_name, cuisine, and rating.
## Key Objectives
- Load and integrate data from CSV, JSON, and SQL sources.
- Clean and preprocess the combined dataset.
- Perform comprehensive exploratory data analysis.
- Answer specific business questions related to:
  . Revenue by city and membership type.
  . Average order value by cuisine.
  . High-value users.
  . Restaurant performance based on ratings and order volume.
  . Seasonal revenue trends.
## Analysis Highlights
Data Integration: All three datasets were successfully merged into a single final_df containing 10,000 orders and comprehensive information.
Data Preparation: Dates were converted, and redundant columns were handled. New features like order_month and order_day_of_week were extracted.
- Overall Order Value: The average order value across all orders was approximately ₹801.16.
- Top Performing City (Gold Members): Chennai generated the highest total revenue from Gold members (₹1,080,909.79).
- Highest Average Order Value Cuisine: Mexican cuisine had the highest average order value (₹826.59).
- Top Revenue Quarter: The 3rd quarter of the year showed the highest total revenue (₹2,037,385.10).
- Restaurant Rating Impact: Restaurants with a 4-5 star rating range generated the highest total revenue (₹4,475,618.43).
- High-Value Users: Users like User_1515 were identified as significant contributors to total spending.
## Conclusion
This analysis provides valuable insights into the food delivery business, identifying key areas for targeted marketing, membership program optimization, and restaurant portfolio management.


## Summary of Questions Answered:
1. City with Highest Gold Member Revenue: Chennai generated the highest total revenue from Gold members, with ₹1,080,909.79.
2. Cuisine with Highest Average Order Value: Mexican cuisine had the highest average order value across all orders, at ₹826.59.
3. Distinct Users with High Order Value: The analysis identified users with total spending above the 75th percentile. For example, User_1515 was a high-value user with the highest total spending of ₹11,556.5.
4. Restaurant Rating Range with Highest Revenue: The rating range of 4-5 stars generated the highest total revenue, amounting to ₹4,475,618.43.
5. City with Highest Average Order Value (Gold Members): Among Gold members, Chennai had the highest average order value, at ₹808.46.
6. Cuisine with Lowest Distinct Restaurants but Significant Revenue: Chinese cuisine, with 120 distinct restaurants, contributed significant revenue of ₹1,930,504.65.
7. Percentage of Orders by Gold Members: 50% of total orders were placed by Gold members.
8. Restaurant with Highest Average Order Value and <20 Orders: Restaurant_294 had the highest average order value of ₹1,040.22 with only 13 total orders.
9. Combination Contributing Highest Revenue: The Regular membership - Mexican cuisine combination contributed the highest revenue of ₹1,072,943.30.
10. Quarter with Highest Total Revenue: The 3rd quarter of the year showed the highest total revenue, with ₹2,037,385.10.
11. Total Orders by Gold Members: 4,987 orders were placed by users with Gold membership.
12. Total Revenue from Hyderabad City: The total revenue generated from orders in Hyderabad city was ₹1,889,367.
13. Number of Distinct Users: There were 2,883 distinct users who placed at least one order.
14. Average Order Value for Gold Members: The average order value for Gold members was ₹797.15.
15. Orders for Restaurants with Rating ≥ 4.5: A total of 3,374 orders were placed for restaurants with a rating of 4.5 or higher.
16. Orders in Top Revenue City among Gold Members: In Chennai (the top revenue city for Gold members), 1,337 orders were placed by Gold members.

