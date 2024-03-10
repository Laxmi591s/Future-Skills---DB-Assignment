Answer No.1:
The relationship between "Product" and "Product_category" entities as per the diagram is a "Many-to-One" relationship. 
Because many products can belong to the same category. And, each product can only have one category assigned to it.
Therefore, each value in the "category_id" column of the "product" table can reference multiple rows in the "id" column of the "product_category" table.


Answer No. 2:
To ensure that each product in the "product" table has a valid category assigned to it, we can do the following steps:
 - Create a FOREIGN KEY constraint on the "category_id" column in the "Product" table that references the "id" column in the "product_category" table. This 
   constraint ensures that every value in the "category_id" column of the "product" table must exist in the "id" column of the "Product_category" table.
 - Also the "id" column in the "product_category" table must be assigned to PRIMARY KEY constraint.
