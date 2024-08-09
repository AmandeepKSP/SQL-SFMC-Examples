### Day 9 – Find Business Admins

NextMobile has two types of customers: business customers and personal customers. The data feed for business customers is slightly different from that of personal customers. The team plans to send a new email about upcoming product changes, specifically targeting administrators for business accounts. Your task is to run a query to find these administrators.

#### Solution
```sql

SELECT 
    id,
    email,
    role
FROM SQL09
WHERE
    role LIKE '%administrator%'
```

## Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.
