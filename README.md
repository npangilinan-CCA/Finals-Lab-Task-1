# [Finals Lab Task 1 - Creating a Database using MySQL Workbench](https://github.com/user-attachments/files/19625279/pangilinan_FinalsLabTask1.docx)
This portfolio is about learning MySQL basics through a multi-level company database. It includes tasks like writing SQL queries, creating table structures, and making an EER diagram or relational schema. The portfolio will also include SQL copies of the database and table structures to show how the database is built.

## Step by Step Process
### Step 1: Create the employees table
- Define employee_id as a unique integer, auto-increment, and primary key.
- Define employee_name as a VARCHAR (up to 255 characters), and make it not null.
- Define manager_id as an integer, which will be a foreign key referencing employee_id from the same table.
  
### Step 2: Create the departments table
- Define department_id as a unique integer, auto-increment, and primary key.
- Define department_name as a VARCHAR (up to 255 characters), and make it not null.
  
### Step 3: Create the employee departments table
- Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.
- Define department_id as an integer, which will be a foreign key referencing department_id in the departments table.
- Set a composite primary key on the combination of employee_id and department_id.
  
### Step 4: Create the employee projects table
- Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.
- Define project_name as a VARCHAR (up to 255 characters), and make it not null.
  
### Step 5: Create the managers table
- Define manager_id as a unique integer, auto-increment, and primary key.
- Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.

## Query Statements
### Task 1
![Image](https://github.com/user-attachments/assets/54f2649a-21ef-4599-a55e-3a9a20f662d3)

### Task 2
![Image](https://github.com/user-attachments/assets/d9495404-9ea9-4c1d-a755-fe8a8c6b50e7)

### Task 3
![Image](https://github.com/user-attachments/assets/d921b6e8-ff68-42ac-9dbd-55fb8c29b5e5)

### Task 4
![Image](https://github.com/user-attachments/assets/b7cadc5d-3099-415e-be3a-44e0e96fa749)

### Task 5
![Image](https://github.com/user-attachments/assets/d0d45768-960a-43ea-86cf-657361b3dcc6)

## Table Structures
### 1. Employee Table
![Image](https://github.com/user-attachments/assets/37ecd6e7-5dcd-4798-b31a-d64a60623ca0)

### 2. Department Table
![Image](https://github.com/user-attachments/assets/f563f728-9e4d-4e8f-98c9-f30180bea9d1)

### 3. Employee Department Table
![Image](https://github.com/user-attachments/assets/f741b000-9512-4c7a-bedb-f451b8f86a57)

### 4. Employee Project Table
![Image](https://github.com/user-attachments/assets/9565e212-3d1e-4a97-93ea-e72eef872a7f)

### 5. Manager Table
![Image](https://github.com/user-attachments/assets/51d1f5e4-8d84-43fc-bb5b-d71ab840121e)

## EER Diagram
![Image](https://github.com/user-attachments/assets/04de19f1-23fb-4666-9730-e0989096f405)


