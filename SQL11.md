### Day 11 – Finding Top Customers

NextMobile had a successful year, and the marketing team wants to identify the top 50 customers who have spent over $2,000 within the year. They plan to send a special gift to these customers. Your SQL expertise is crucial in identifying this valuable audience.

#### Solution
```sql
SELECT TOP 50 id,amount FROM SQL11
WHERE amount > 2000
ORDER BY amount DESC
```

## Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.



