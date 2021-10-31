# Get script to create existing table and its data
Can be useful to send it to someone or have a backup

- Connect to DB
- right click on "DB_name" > "Tasks" > "Generate Scripts" > next
- expand "tables" > select tables needed
- "save as script" > note where .sql file will be saved > "advanced" > end of "general" change "type of data to script" to "Schema and data"
- next > next


# Delete all data and reset index in a table
```truncate table TableName```