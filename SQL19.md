### Day 19 – Calculating Quarterly Sales

The NextMobile team is analyzing last year's sales to guide future campaigns. They require a breakdown of 2023's sales by quarter to identify performance highs and lows. Your role is to use a SQL query to segment and summarize our sales data for each quarter.

Today's task is about drawing insights from time series data. You'll use the handy DATEPART function to pull out the quarter component from each date in your dataset. Pair this with GROUP BY for a clean summary of sales figures by quarter.

#### Solution
```sql
SELECT 
DATEPART(quarter, date) AS quarter,
SUM(amount) AS total_sales
FROM SQl12
WHERE status = 'shipped'
GROUP BY DATEPART(quarter, date)

```
## Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.
