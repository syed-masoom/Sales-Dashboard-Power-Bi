# Sales-Dashboard-Power-Bi in Detailed Explanation

# Purpose of this Analysis
Mobile E-Store, want to improve conversion rates on mid-range phones.
They want to understand why people buy mid-range phones like Realme and Pixel models — and what drives those decisions. Should we emphasize gaming, performance, or price in our campaigns?"

# In this Content you will Know 
1. Our task on the Basis of this Scenario.
2. Data Sources.
3. Data Preparation for Power Bi.
4. Dashboard & Visuals I Created
5. Overall Business Performance
6. Mid-Range-Phone Performance
7. Top 10 Best Selling Mid-Range-Phone
8. Action Plan
9. Key Takeways
10. Conclusion

# 1. Our Task On the Basis of this Scenario
1. Analyze which purchase reasons are most associated with specific phone brands.
2. Understand if income levels impact those reasons (e.g., low-income customers choosing price over performance).
3. Check if models with higher ratings share common patterns (e.g., reasons for purchase or preferred payment method).
4. Recommend 3–4 actionable marketing strategies based on these insights (e.g., banners like “Top Rated by Friends” or “Best Performer Under ₹40K”).

# 2. Data Sources
I Created this dataset using ChatGpt based on a prompt where I Give Prompt to ChatGpt to Generate dataset 
Where I specified necessary columns for the sales data of a mobile store and data format then I followed the following steps.
1. When dataset is generated I Download that dataset and Import in excel for further data cleaning and processing for errorless analysis
   because this dataset was Ai Generated so some of the was not presented so did this in Excel
2. Then I use Calculate some column using SUM Function.
3. The was in two tables Order table and Customer Table I merged this Data in one table Using Excel Built in function Like Vlookup, Xlookup, Sumif and more.
4. And Leave some data Prepration task for Power bi which i did on Power Bi
5. After Completing all the data cleaning and data processing steps I Export this dataset for further reporting in Power Bi

# 3. Data Prepration for Power Bi
1. Loaded the cleaned dataset into Power BI.
2. Transformed the data using Power Query Editor.
3. Created new calculated columns using DAX, such as:
    Price Range (Affordable, Mid-Range, Expensive)
    Rating Category (Satisfied, Good, Not Satisfied)
4. Built the dashboard visuals to help explore the patterns.

# 4. Dashboard & Visuals I Created
1. KPIs: Revenue, Total Orders, Average Rating, and Profit
2. Doughnut Chart: Sales by Purchase Reason
3. Pie Chart: Sales by Payment Method
4. Stacked Column Chart: Sales by Income Level + Purchase Reason
5. Bar Chart: Revenue by Phone Model
6. Slicers: Price Range and Rating Filter

# 5.  Overall Business Performance
1.	Total Revenue: ₹655.23M
2.	Total Orders: 10,000
3.	Average Rating: 4.0
4.	Total Profit: ₹71.58M

# 6. Mid-Range-Phone Performance
Mid-Range Phone Segment Performance
⦁	Revenue: ₹154.37M
⦁	Total Orders: 4,073
⦁	Average Rating: 4.0
⦁	Profit: ₹21.54M

Top Purchase Reasons for Mid-Range Phones.
⦁	Gaming     | Orders 1,868  | Revenue ₹93.99M | Profit ₹12.48M | Share 45.86% |
⦁	Features    | Orders 1,782  | Revenue ₹53.06M | Profit ₹7.96M  | Share 43.75% |
⦁	Performance  | Orders 423    | Revenue ₹7.33M  | Profit ₹1.1M   | Share 10.39% |

⦁	Customers care more about gaming and features than just raw performance.
⦁	Marketing should focus on fun, feature-packed user experiences.

% of Orders by Payment Methods
⦁	Debit Card - 36.53% of Orders.
⦁	UPI - 27.42%  of Orders.
⦁	Cash - 18.17% of Orders.
⦁	Bank Transfer - 17.87% of Orders.

Digital payments dominate, showing that our users are tech-savvy and digitally inclined.
Campaigns offering UPI/debit card cashback or instant discounts may boost conversions.

Sales by Income Level and Purchase Reasons
⦁	Low - | Gaming 16.06% |	Features 14.98% | Performance 3.73% |.
⦁	Medium - | Gaming	14.90% | Features	14.83% | Performance 3.44% |.
⦁	High - | Gaming 14.90%	| Features 13.95% | Performance 3.22% |.

Across all income groups, Gaming and Features are consistent top priorities.
So, value-for-money matters more than just affordability.

   

