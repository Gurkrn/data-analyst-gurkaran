# data-analyst-gurkaran
# Project Title: Titanic Survival Analysis
Objective and Aim
This project aims to analyze the survival rates of Titanic passengers based on various factors such as passenger class, gender, and overall demographics. Using exploratory data analysis (EDA) and visualization techniques, we identify key trends and patterns in survival outcomes, providing insights into the factors that influenced survival during the disaster.

Methodology
The dataset used for analysis is the Titanic dataset, which contains details about passengers, including their class, gender, age, fare, and survival status.

Data preprocessing involved handling missing values, categorizing variables, and performing statistical calculations.

Exploratory Data Analysis (EDA) was conducted using Python libraries such as Pandas, Seaborn, Matplotlib, and Plotly to visualize survival distributions.

A dashboard was built using Dash and Plotly to present survival analysis interactively.

Key visualizations include:

Overall Survival Rate (Pie Chart) – Displays the proportion of survivors and non-survivors.

Survival Rate by Passenger Class (Bar Chart) – Illustrates how survival rates differed across first, second, and third-class passengers.

Results and Findings
    The overall survival rate was 36.4%, while 63.6% of passengers did not survive.

Survival rates by passenger class:

    First-class: 46.7% survival rate.

    Second-class: 32.3% survival rate.

    Third-class: 33.0% survival rate.

First-class passengers had the highest survival rate, suggesting a strong correlation between socioeconomic status and survival probability.

Women and children had a significantly higher survival rate, reinforcing the "women and children first" evacuation policy.

Third-class passengers had the lowest survival rates, likely due to their cabins being in the lower decks, limiting accessibility to lifeboats.

## Visualizations

### 1. Overall Survival Distribution  
![Overall Survival Distribution](https://github.com/Gurkrn/data-analyst-gurkaran/blob/84cfd24633ca0d2ee40aac364ae0ea1ce974672d/newplot.png?raw=true)

### 2. Survival Rate by Passenger Class  
![Survival by Class](https://github.com/Gurkrn/data-analyst-gurkaran/blob/84cfd24633ca0d2ee40aac364ae0ea1ce974672d/Survival%20pass.png?raw=true)


Conclusion
This analysis demonstrates how socioeconomic status, gender, and class significantly influenced survival on the Titanic. The findings provide valuable insights into historical survival patterns and highlight the potential for further predictive modeling. Future work could involve applying machine learning algorithms to predict survival outcomes based on passenger attributes, enhancing data-driven decision-making in similar scenarios.

# PROJECT 2


# Understanding Customer Purchase Patterns at XYZ Retail
Objective
The goal of this project is to conduct a descriptive analysis of customer purchase patterns at XYZ Retail. By analyzing transaction data, we aim to identify key trends, consumer behaviors, and insights that can inform marketing strategies and inventory management.

Methodology
Data Collection & Preparation

Generated a synthetic dataset of 1,000+ transaction records with key details such as Transaction ID, Customer ID, Purchase Date, Product Category, Quantity, Price, Payment Method, and Store Location.

Cleaned the data by addressing missing values and correcting data types.

Descriptive Analysis & Visualization

Sales Trend Over Time: Analyzed total transactions per month to identify peak shopping periods.

Top Product Categories: Identified the most frequently purchased product categories.

Payment Method Distribution: Examined customer preferences for different payment options.

Customer Segmentation & Insights

Segmented customers based on purchase frequency and behavior.

Derived insights to optimize inventory, promotions, and marketing strategies.

Results & Findings
📊 Sales Trend Over Time

The highest number of transactions occurred in August 2023 (104 transactions), indicating a peak shopping period, possibly due to seasonal promotions.

### **1. Sales Trend Over Time**  
![Sales Trend Over Time](https://github.com/Gurkrn/data-analyst-gurkaran/blob/383ad10e6ea53f4404015d7f66c3abac50ea457b/newplot%20(1).png?raw=true)  


🛒 Top Product Categories
The most purchased category was Furniture (226 purchases), followed by Toys (209), Clothing (203), Electronics (193), and Groceries (169).

### **2. Product Category Distribution**  
![Product Category Distribution](https://github.com/Gurkrn/data-analyst-gurkaran/blob/383ad10e6ea53f4404015d7f66c3abac50ea457b/newplot%20(2).png?raw=true)  

💳 Payment Method Preferences
Digital Payments (344 transactions) were the most used method, slightly ahead of Cash (335 transactions) and Credit Cards (321 transactions).

### **3. Payment Method Preferences**  
![Payment Method Preferences](https://github.com/Gurkrn/data-analyst-gurkaran/blob/383ad10e6ea53f4404015d7f66c3abac50ea457b/newplot%20(3).png?raw=true) 

# Key Insights & Recommendations

✅ Peak Shopping Periods: August had the highest transactions, suggesting seasonal trends that XYZ Retail can leverage through targeted marketing campaigns.

✅ Inventory Planning: Furniture and Toys had the highest purchase volumes, indicating a need for adequate stock levels and possible cross-promotions between these categories.

✅ Payment Preferences: The shift toward digital payments suggests an opportunity to introduce loyalty rewards or exclusive discounts for online or mobile transactions.

By leveraging these insights, XYZ Retail can optimize inventory management, pricing strategies, and customer engagement, ultimately improving sales and customer satisfaction. 🚀


# Project 3

# Diagnostic Analysis of Sales Decline at XYZ Retail

Objective & Aim

This project investigates the reasons behind the decline in sales at XYZ Retail over the past year. By analyzing sales trends, customer behavior, and transaction data, the goal is to identify key patterns and correlations that explain the downturn. The findings will provide actionable recommendations for improving sales performance and optimizing business strategies.

Methodology
Trend Analysis

Examined monthly sales trends to identify periods with the most significant sales declines.

Correlation Analysis

Conducted statistical regression analysis to measure the relationship between sales and variables such as time, inventory levels, customer behavior, and external factors.

Root Cause Analysis

Used techniques such as the "5 Whys" and Fishbone Diagram to explore potential causes, including operational inefficiencies, competitive influences, and consumer behavior shifts.

Segmentation Analysis

Categorized customers based on spending behavior and location to determine which groups are most affected by the decline.

Results & Key Findings
Sales have shown a steady decline over time, with an estimated monthly drop of approximately $1,317, as confirmed by regression analysis (p = 0.007).

The most significant declines were observed in July and November, indicating possible seasonal trends or external economic factors.

Furniture and Electronics were the best-selling product categories, with total sales of $83,637 and $77,682, respectively.

Digital payments accounted for the highest transaction amounts ($134,767), suggesting a shift toward online and cashless payments.

Customers in Chicago and Los Angeles had the highest average transaction values (~$267), while those in New York had the lowest ($243), highlighting regional differences in purchasing behavior.

Visualizations & Findings
1. Trend Analysis: Sales Decline Over Time
Monthly sales data revealed a downward trend, with the most significant declines observed in July and November.

Regression analysis indicated a strong negative correlation between time and sales, with an average monthly decrease of approximately $1,317.


2. Correlation Analysis: Sales vs. Other Factors
Regression results suggest that time is a significant predictor of sales decline (p = 0.007).

External factors, such as inventory levels and changing consumer spending habits, may also contribute to the decline.


3. Root Cause Analysis
Potential causes identified include seasonal demand fluctuations, shifts in payment preferences, and regional differences in customer spending.

Further qualitative research, such as staff interviews and customer feedback analysis, could provide deeper insights.


4. Segmentation Analysis: Customer Behavior
High-spending customers were primarily located in Chicago and Los Angeles, with average transaction values above $260.

New York customers had the lowest average spending (~$243), suggesting potential regional differences in purchasing power or preferences.



Conclusion & Recommendations
Implement targeted pricing strategies and promotions during months with the steepest declines.

Strengthen digital payment and e-commerce capabilities to cater to changing customer preferences.

Develop location-specific marketing campaigns to improve sales in underperforming regions such as New York.

Conduct customer surveys to gain qualitative insights into shifting consumer preferences.

Optimize inventory management to ensure product availability aligns with demand patterns.
