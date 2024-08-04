### Day 3 - Find Eligible Customers

NextMobile is planning a promotion for customers who use less than 20GB of data in a month. Before finalizing the offer, the marketing team wants to determine the number of customers in this category.

#### Solution
```sql
Select id As eligible_customer from SQL03
where data_usage < '20'
```

### Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.