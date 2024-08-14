### Day 17 – Engage with new customers

NextMobile's latest marketing strategy involves an exclusive promotional campaign specifically for accounts established within the last 90 days. Your task is to identify these accounts and add them to the campaign as new accounts become eligible.

Today's challenge involves using the DATEDIFF function to identify orders from 2023 that were delayed by more than 7 days. This information is crucial for NextMobile’s operations team to understand the extent of the delays and implement corrective actions.

#### Solution
```sql
SELECT id, launch_date
FROM SQL17
WHERE launch_date >= DATEADD(DAY, -90, GETDATE()) 
AND launch_date < GETDATE()
```

## Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.
