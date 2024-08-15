### Day 15 – Find High User-Density States

NextMobile plans to launch a pilot promotional offer and is considering running it in states with a high user base. The marketing team needs to identify the states where the majority of their users are located, specifically focusing on states with more than 50 users.

#### Solution
```sql
SELECT 
    state, 
	COUNT(id)
FROM SQL13
GROUP BY 
    state
HAVING COUNT(id) > 50
```

## Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.






