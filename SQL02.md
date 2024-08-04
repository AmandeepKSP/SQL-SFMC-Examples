###  Day 2 - Identify User Groups

NextMobile has just launched a new "Gigabit Fibe 1.5" Internet package. The marketing team is eager to notify all users who haven't yet upgraded to this new package. Your task is to identify these users.

#### Solution
```sql
Select id, internet_package from SQL02
where internet_package != 'Gigabit Fibe 1.5'
```

### Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.
