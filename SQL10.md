### Day 10 – Check Missing Data

While preparing the email regarding the upcoming product changes for administrators of business accounts, the team noticed that some administrators do not have any phone information. The team is curious if you can identify those administrators who are missing a phone number.

#### Solution
```sql

SELECT 
    id,
    email,
    role,
    phone
FROM SQL10
WHERE
    role LIKE '%administrator%' AND phone IS NULL
```

## Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.



