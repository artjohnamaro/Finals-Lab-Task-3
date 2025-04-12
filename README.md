# Finals Lab Task 3: [Table Manipulation](https://github.com/user-attachments/files/19716402/FINAL.LAB.TASK.3.pdf)
This portfolio illustrates the development of foundational MySQL skills through the creation and management of a product database. The activity involves designing a table structure, applying constraints, inserting valid product records, and modifying table attributes. These tasks collectively demonstrate the practical application of basic SQL commands to organize and maintain an efficient database system.

## Step By Step Process
**Step 1: Table Creation**

Establish a table named products with the following attributes:

- id: An integer field set to auto-increment and designated as the Primary Key to uniquely identify each product.

- product_name: A VARCHAR(100) field that cannot be NULL, ensuring each product has a valid name.

- price: A DECIMAL field to store the product's monetary value.

**Step 2: Constraint Definition**

Introduce a CHECK constraint on the price column to enforce a business rule that all product prices must be greater than zero.

**Step 3: Inserting Valid Records**

Populate the products table with entries that meet the defined constraints. Only include products with positive prices. Valid examples include:

- Laptop – 999.99

- Smartphone – 599.99

- Tablet – 299.99

- Keyboard – 19.99

- Mouse – 14.99

- Desk Lamp – 24.99

- Speakers – 9.99

" Products with negative price values are excluded to maintain data integrity. "

**Step 4: Table Modification**

Alter the structure of the product_name column by increasing its character limit from 100 to 120, allowing for more descriptive product names while preserving existing data.

## QUERY STATEMENT
TASK 1:
- ![Image](https://github.com/user-attachments/assets/5bf160eb-2d98-4f2d-98b2-953d6fdfe068)
  
TASK 2:
- ![Image](https://github.com/user-attachments/assets/df5d7668-9b6b-4f9a-a4f8-5e077015ab43)
  
TASK 3:
- ![Image](https://github.com/user-attachments/assets/bb603673-870f-41bf-afc4-b608df5aee44)
  
TASK 4:
- ![Image](https://github.com/user-attachments/assets/d8359fee-6a02-4b42-83c3-44ccb8cc5746)

## TABLE STRUCTURE 
TABLE STRUCTURE 1:
- ![Image](https://github.com/user-attachments/assets/a3568aa2-b0ec-4bac-9863-bc83b79f255e)

TABLE STRUCTURE 2:
- ![Image](https://github.com/user-attachments/assets/d4f56b50-8b61-4a12-a586-3d7d119fc406)

## ER DIAGRAM
- ![Image](https://github.com/user-attachments/assets/909e0d47-aed0-4776-9e0a-23aaa0410d7c)
