### Day 13 – Spotting Unique Addresses

NextMobile is organizing a special event to thank their customers. They want to give exclusive e-vouchers to their users. But they have a rule of sending only one voucher per house, based on one address. Your job is to make a list of all different addresses from the database to make sure that no house gets more than one voucher.

#### Solution
```sql
SELECT 
    DISTINCT CONCAT_WS(',', address, city, state, postal_code, country)
FROM SQL13
```

## Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.





