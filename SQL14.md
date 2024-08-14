### Day 14 – Segment Your Customers

NextMobile offers a range of mobile plans. For an upcoming campaign, they would like to categorize users based on their monthly usage. The criteria are as follows:

Heavy users: Use more than 50GB
Moderate users: Use more than 25GB
Light users: Use less than 25GB
Your task is to classify users based on these criteria, but exclude those who haven't used any data.

#### Solution
```sql
SELECT id, data_usage,
CASE 
    WHEN data_usage > 50 THEN 'Heavy'
    WHEN data_usage > 25 THEN 'Moderate'
    ELSE 'Light'
END AS user_type
FROM SQL03
WHERE 
    data_usage != 0
```

## Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.






