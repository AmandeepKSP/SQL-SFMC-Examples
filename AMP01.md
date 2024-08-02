# Day 1 – Export Users

## NextMobile is getting ready for its monthly customer newsletter, and the marketing team needs a list of customer users with their email addresses, first names, and last names from the primary database. As a member of the marketing team, your responsibility is to extract this data from the database and send it to the marketing team.

### Solution

```sql
SELECT email_address, first_name, last_name
FROM users;

### Resources

Download the sample dataset from the `SQL-CSV` folder to start practicing.