# STRUCTURED QUERY LANGUAGE
This is the overview of theis repo.
This repo is designed as a structured SQL class where students will be assigned practical SQL-related tasks to enhance their understanding and proficiency

## TASK SUBMISSION AND DOCUMENTATION GUILDLINES
Students are expected to submit their SQL task files in this section, ensuring each submission is properly documented and committed with clear, descriptive messages.

### STANDARD QUERY FORMAT AND SYNTAX
This section outlines the best practices for writing SQL queries, including formatting, naming conventions, and optimization tips for clarity and efficiency.
And this is how we should endeavor to write our queries and commands.

```SQL
SELECT *
FROM emptable
WHERE language = 'Love'
;
```

### Task DONE
* Create a new schema called 'Tasks' 
* Create a tables 'Design','Operations' in the created database. 
* Show the records in the World database under the city table.
* Show the fields name, continent and governmentform in the country table.

### Task DONE
* Provide fields; jobtitle and salary to the table guys from the class example.
* The jobtitle are (data analyst, data scientist), populate for the records however you want.
* The field salary should be in a way that it could take a null value for some of the records.
* The salary field should be of 6 figures with indication for the kobo too.

### Task DONE
First tasks is to type your name in the bench work and submit it

Design and implement a schema for a E-commerce platform with the following tables
using appropriate data types and constraints (e.g primary, forign,null):
1. Customers
- customer_id (primary key)
- name
- phone_number
- address (street, city)

2. Products
- product_id (primary key)
- product_name
- category
- price
- stock_quantity

3. Orders
- order_id (primary key)
- customer_id(foreign key)
- order_date
- total_amount

4. order_items
- order_item_id (primary)
- order_id (foreignkey referencing orders)
- product_id (foreign key)
- quantity
- price

2. Tasks
* populate the tables with at least:
- 10 customers
- 10 products
- 15 orders
- 20 order items

Write queries to perform the following operation
1. Read what is in all the tables.
2. Add a new customer to the database.
3. Update the stock quantity of a product after a purchase.
4. Delete an order from the database.
5. Retrieve all orders made by a specific customer.

### Task PENDING
1. Which departments show the most diversity in terms of race and gender combinations?
2. Identify job roles where the gender distribution is highly unbalanced.
3. What is the distribution of races across remote versus on-site employees?
4. How many employees aged 30 or younger work in Engineering or Product teams?
5. Which cities employ the highest number of Hispanic or Latino staff?
6. Which department has retained the highest number of employees hired before 2010?
7. Identify job titles that are exclusive to only one location or city.
8. Which state has the widest range of job titles represented among its employees?
9. Find the average age of employees in each department.
10. Which departments have more female employees than male employees?
