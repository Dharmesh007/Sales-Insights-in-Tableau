# Sales-Insights-in-Tableau

AIM: The main aim of the project was to create an automated dashboard providing quick & latest sales insights in order to support data driven decision making.

# Data- Attributes details
There are 5 tables. So, to combine all the tables I followed STAR SCHEMA approach, wherein the transaction table is our Fact table and all other tables mentioned below(Other then transaction table) are our Dimensions tables  
- customer table - It contains details of all the clients of AtliQ hardware (Customer_code & Customer_name) 
- transaction table - It contains all the transactions details (product_code, customer_code, market_code, order_date, sales_qty, sales_amount)
- products table -  It contains (product_code, product_type- OwnBrand,Distribution)
- market table - It contains market names and zones (markets_code, markets_name, zone)
- date table - It contains (date, cy_date(1st date of every month), year, month_name, date_yy_mmm)

The dimension table is joined to the fact table(transaction table) using a foreign key.

The Sales Director wants to know answers to the below mentioned questions:
- Who are my Top 5 customers 
- What are my 2 weakest regions where sales are declining
- What is my aggregate revenue in last 365 days
- Revenue breakdown by cities
- Top 5 products by revenue number
and etc.

## Link to the Dashboard - (Click the link given below)👍
https://public.tableau.com/views/SalesInsightsDashboard_16086159611580/Dashboard-ProfitAnalysis?:language=en&:display_count=y&:origin=viz_share_link
  
Completely Interactive dashboards 👆👆👆   
      
1) Dashboard - Revenue Analysis

![Dashboard - Revenue Analysis](https://user-images.githubusercontent.com/59524152/102855409-9ac80300-444a-11eb-8742-d7bd84a0e6b7.JPG)


2) Dashboard - Profit Analysis

![Dashboard - Profit Analysis](https://user-images.githubusercontent.com/59524152/102855794-48d3ad00-444b-11eb-9d3b-ec64fdbe0865.JPG)

# Conclusion (Success criteria of this project)
- Dashboard(s) uncovering sales order insights with latest data available
- Sales team were able to take better decisions and prove 10% cost savings of total spend
- Sales Analysts stop data gathering manually in order to save 20% of their business time and reinvest it value added activity

