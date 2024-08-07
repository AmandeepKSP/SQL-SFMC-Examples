### Day 7 – Calculate between values

One of the goals of the NextMobile marketing team is to promote their data plans and send new offers to existing customers based on their data usage. The team wants to launch a new campaign targeting existing customers whose data usage falls between 50 and 75 percent. Your task is to identify the eligible customers.

#### Solution
```sql

SELECT 
    id,
    data_usage,
    data_plan
FROM SQL07
WHERE 
    data_usage / data_plan BETWEEN 0.5 AND 0.75
```

## Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.
