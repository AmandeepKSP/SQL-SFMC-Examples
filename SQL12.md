### Day 12 – Order Status Analysis

The NextMobile marketing team is keen to understand the patterns in orders for 2023. Your task is to provide a summary of orders by their status, detailing the count, total amount, and status for each order type. This data is crucial for strategic decision-making and customer satisfaction improvement.

#### Solution
```sql
SELECT status, COUNT(amount), SUM(amount) FROM SQL12 GROUP BY status
```

## Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.



