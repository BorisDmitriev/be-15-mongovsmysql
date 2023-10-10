# Exercise Task: Understanding Database Concepts

## Introduction
This exercise task focuses on basic database concepts, specifically table / collection, row / document, column / field, and key / ID. You will learn practical examples of both MongoDB and SQL and apply these concepts.

## Tasks

### Task 1: Create a Collection in MongoDB
Create a collection in MongoDB using the `db.createCollection()` command. Verify that the collection was created successfully by using the `show collections` command.

### Task 2: Creating a table in SQL
Create a table in SQL using the `CREATE TABLE <table name> (<column definitions>)` command. Use appropriate column definitions for your table. Verify that the table was created successfully by using the `SHOW TABLES` command.

### Task 3: Differences between table and collection
Briefly describe the difference between a table and a collection in terms of their structure and usage. Provide the answer as a Markdown comment in your README.md file.


### Answer:   
###  1) In SQL, you have to create a table and define the data types; In mongoDB, you can't create a collection, it creates itself automatically when inserting data.
###  2) In SQL, you must insert values as per data types; In mongoDB, you can insert values of any types.
###  3) In SQL, you can't create a column at insert or update time; In mongoDB, it is possible.
###  4) In SQL, almost nothing is case sensitive; In mongoDB, everything is case sensitive .


#### Task 4: Inserting a document into MongoDB

Insert a document into the collection you created earlier in MongoDB. Use the `db.<collection>.insertOne(<document>)` command. The document should contain relevant fields that match the structure of your collection.

### Task 5: Inserting a row in SQL
Insert a row into the table you created earlier in SQL. Use the command `INSERT INTO <table name> VALUES (<values>)`. Enter the appropriate values for your table.

### Task 6: Differences between row and document
Briefly describe the difference between a row and a document in terms of how they are used and created. Provide the answer as a Markdown comment in your README.md file.

  ### Answer: While rows in the relational world are made up of columns, documents contain properties.


### Task 7: View all documents in MongoDB
Retrieve all documents from the created collection in MongoDB. Use the `db.<collection>.find({})` command. Verify that the retrieved documents contain the expected content.

### Task 8: Displaying all rows in SQL
Retrieve all rows from the created table in SQL. Use the `SELECT * from <table name>` command. Check if the retrieved rows contain the expected content.

### Task 9: Differences between column and field
Briefly describe the difference between a column and a field in terms of their usage and presentation. Provide the answer as a Markdown comment in your README.md file.


  ### Answer: A column is a collection of cells alligned vertically in a table. A field is an element in which one piece of information is stored, such as the 'ID' field.


### Task 10: Adding IDs to SQL Table
Add a single

ular ID column to your SQL table. Use the command `CREATE TABLE <table name> (id NOT NULL AUTO_INCREMENT, <column definitions>, PRIMARY_KEY(id))`. Make sure that the id is automatically incremented and set as the primary key.

## Notes

- For more information about the commands and concepts, you can consult the corresponding documentation:
  - [MongoDB Documentation](https://docs.mongodb.com/)
  - [SQL Documentation](https://www.w3schools.com/sql/)

- Take screenshots of the expected results for the examples and paste them into the "Example" section of your README.md file.

Good luck with the exercise task!
