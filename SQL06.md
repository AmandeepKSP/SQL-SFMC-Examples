### Day 6 – Use Combined Conditions

NextMobile has a customer community website and wants its customers to actively participate in the community. Your task is to identify customers who have an active app profile but haven't logged into the community in the last 12 months.

#### Solution
```sql
Select id As eligible_customer from SQL06
where is_active ='True' AND logged_12_months = 'False'
```

## Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.
