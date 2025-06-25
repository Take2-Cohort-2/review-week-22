
# SQL Test: Food Orders and Customer Database

## **Test Overview:**

In this test, you will create a database for tracking food items and orders in a restaurant or kitchen scenario. You will create tables, insert data, and write SQL queries to retrieve information. At the end of the test, you will export your entire database and submit the export file for review.

---

## **Part 1: Table Creation**  
**(20 marks)**

You are required to create the following tables in your database. When creating each table, you will need to determine the appropriate **data types** for each column, such as `INTEGER`, `VARCHAR`, `TIMESTAMP`, etc. 

1. **MealTypes Table**:  
   - **Columns**:  
     - `MealTypeID`  
     - `Name`  
     - `CreatedOn`  

2. **Customers Table**:  
   - **Columns**:  
     - `CustomerID`  
     - `Name`  
     - `Age`  

3. **FoodItems Table**:  
   - **Columns**:  
     - `FoodItemID`  
     - `Name`  
     - `Calories`  
     - `MealTypeID`  

4. **Orders Table**:  
   - **Columns**:  
     - `OrderID`  
     - `CustomerName`  
     - `FoodItemID`  
     - `Quantity`  
     - `DayOfWeek`  
     - `CreatedOn`  

---

## **Part 2: Data Insertion**  
**(30 marks)**

Now that you have created the tables, you need to insert some data into them. Below are the instructions for inserting the data. **You will need to determine the insert statements on your own**.

### **Customer Data**:
Insert **three customers** into the `Customers` table:

1. Jack Roberts, Age: 30  
2. Sophie Wilson, Age: 28  
3. Liam O'Connor, Age: 35  

### **Food Item Data**:
Insert **three food items** into the `FoodItems` table:

1. Sandwich, 250 Calories, Meal Type: Breakfast  
2. Burger, 400 Calories, Meal Type: Lunch  
3. Curry, 500 Calories, Meal Type: Dinner  

### **Order Data**:
Insert **three orders** into the `Orders` table:

1. Jack Roberts ordered Sandwich (Qty: 2) on Monday  
2. Sophie Wilson ordered Burger (Qty: 1) on Tuesday  
3. Liam O'Connor ordered Curry (Qty: 3) on Wednesday  

---

## **Part 3: SQL Queries**  
**(20 marks)**

Send on Slack: Write SQL queries to answer the following:

1. Meals ordered on Wednesday (10 marks)  
2. Orders by Liam O'Connor (5 marks)  
3. Orders by Sophie Wilson on Tuesday (5 marks)

---

## **Part 4: Update Task**  
**(10 marks)**

After the teacher helps you create the `MealTypes` table with Breakfast, Lunch, and Dinner, write a query to update "Lunch" to "Snack".

---

## **Part 5: Export and Submission**  
**(5 marks)**

Export your full database to a `.sql` file and submit it.

sqlite> .output yourname.sql
sqlite> .dump
sqlite> .exit

---

### **Grading Summary (Total: 100 Marks)**

- Table creation: 20 marks  
- Data insertion: 30 marks  
- SQL queries: 20 marks  
- Update task: 10 marks  
- Export: 5 marks  
