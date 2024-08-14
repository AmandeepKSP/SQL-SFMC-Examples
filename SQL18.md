### Day 18 – Identify Delayed Orders

In response to customer feedback regarding delayed orders, our team is conducting a detailed review. We aim to identify orders that were shipped more than 7 days after being placed. Your task is to execute a SQL query that will bring these orders to light, allowing us to address and rectify these delays promptly.

#### Solution
```sql

SELECT 
    order_id, 
    date AS order_date, 
    ship_date
FROM SQl18
WHERE 
    DATEDIFF(day, date, ship_date) > 7
    AND status = 'shipped'
```
## Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.
