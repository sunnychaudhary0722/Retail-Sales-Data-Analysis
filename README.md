# Walmart Sales Data Analysis

## Project Overview
This project explores Walmart sales data to identify top-performing branches and products, uncover sales trends, and understand customer behavior. Insights from this analysis can help optimize sales strategies and improve overall revenue. The dataset is sourced from the Kaggle Walmart Sales Forecasting Competition, covering transactions from three branches: Mandalay, Yangon, and Naypyitaw.

## Objective
- Identify best-selling products and product lines  
- Analyze sales trends across days, weeks, and months  
- Understand customer segments, preferences, and profitability  
- Evaluate branch performance and revenue drivers  

## Dataset
- **Rows:** 1,000  
- **Columns:** 17  
- **Key Columns:** `invoice_id`, `branch`, `city`, `customer_type`, `gender`, `product_line`, `unit_price`, `quantity`, `VAT`, `total`, `date`, `time`, `payment_method`, `COGS`, `gross_margin_percentage`, `gross_income`, `rating`  

## Approach
1. **Data Cleaning & Wrangling**: Handle missing values and ensure data consistency  
2. **Feature Engineering**: Add `time_of_day`, `day_name`, and `month_name` columns to analyze sales patterns by time and season  
3. **Database Creation**: Store data in a structured SQL database for querying and analysis  
4. **Exploratory Data Analysis (EDA)**: Examine product performance, sales trends, customer segments, and revenue patterns  

## Key Insights
- Top-performing product lines and branches  
- Peak sales times and busiest days of the week  
- Customer behavior and preferred payment methods  
- Revenue, VAT, and profit analysis by product line and branch  

## Revenue & Profit Calculations
- **COGS** = `unit_price * quantity`  
- **VAT** = `5% of COGS`  
- **Total Revenue** = `COGS + VAT`  
- **Gross Profit** = `Total Revenue - COGS`  
- **Gross Margin %** = `Gross Profit / Total Revenue`
