### Day 5 – Use Multiple Criteria

NextMobile is preparing an upsell offer for existing customers. They would like to target customers who have the "Essential 120" mobility package or the "Fibe 500" internet package. Your task is to generate a list of these users

#### Solution
```sql
Select id, email, internet, mobility from SQL05
Where internet = 'Fibe 500' OR mobility = 'Essential 120'
```

## Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.
