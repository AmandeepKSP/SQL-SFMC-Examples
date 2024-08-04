### Day4 - Multiply Bonus Points

NextMobile is preparing for their annual bonus redemption event. During this event, customers can convert their loyalty points at a rate of 1.5 times their current points. The marketing team wants to identify customers who, after applying this bonus conversion rate, will have 150,000 points or more.

#### Solution
```sql
Select id As eligible_customer from SQL04
where (points*1.5) >= 150000
```

## Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.
