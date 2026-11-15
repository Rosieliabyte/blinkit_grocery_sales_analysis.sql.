Blinkit Grocery Sales Analysis (SQL)

SQL analysis of Blinkit grocery sales data. Cleaned inconsistent labels, calculated 4 core KPIs (total sales, average sales, average rating, item count), and analysed performance across fat content, item types, outlet size, location tier, outlet type, and price range.

Dataset
Source: Blinkit dataset on Kaggle
File used: BlinkIT Grocery Data.csv
Columns: Item_Fat_Content, Item_Type, Item_MRP, Outlet_Size, Outlet_Location_Type, Outlet_Type, Item_Visibility, Item_Rating, Sales
Skills Used

SQL, KPI calculation, data cleaning, GROUP BY, ORDER BY, CASE WHEN, aggregate functions (SUM, AVG, COUNT, ROUND)

Project Files
File	Description
blinkit_grocery_sales_analysis.sql	Table creation, data cleaning, KPI and analysis queries
Blinkit_Project_Report.pdf	Project explanation
Blinkit_Dataset_Overview.pdf	Dataset structure and cleaning notes
How to Run
Download BlinkIT Grocery Data.csv from the Kaggle link above.
Create the blinkit table using the first block of blinkit_grocery_sales_analysis.sql.
Import the CSV into the table.
Run the cleaning and analysis queries in the same file.
Data Cleaning

Item_Fat_Content had inconsistent labels, which were standardised:

LF and low fat → Low Fat
reg → Regular
KPIs
KPI	Description
Total Sales	Sum of all sales
Average Sales	Average sales per item
Average Rating	Average customer rating
Total Items	Number of items in the data
Business Questions Answered
Do customers prefer Low Fat or Regular items?
Which item types generate the most revenue?
How does performance differ by outlet size?
Which location tier performs best?
How do sales differ by outlet type?
Which MRP price range drives the most sales?
Which outlet type and location combination performs best?
Key Findings

Add your results here after running the queries.

Total revenue:
Low Fat vs Regular:
Most profitable outlet size:
Best performing city tier:
Best MRP price range:

