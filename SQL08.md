### Day 8 – Query Multiple Values

NextMobile has recently launched three new data plans: "Esssential", "Flex", and "Flex Plus". The marketing team would like to send a thank-you email to users who have subscribed to any of these plans. Your task is to generate a list of these recent subscribers.

#### Solution
```sql
SELECT 
    id,
    data_plan
FROM SQL08
WHERE
    data_plan IN ('Flex', 'Flex Plus', 'Essential')
```

## Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.
