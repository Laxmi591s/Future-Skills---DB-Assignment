Answer No.1:
The relationship between "Product" and "Product_category" entities as per the diagram is the "One-to-One" relationship. 
As the diagram shows, there is only one common link between the table "Product" and "Product_category".
So this relationship says, that one Product can only have one Product_category.


Answer No. 2:
We can ensure that each product in the "Product" table has a valid category assigned to it, by checking the below conditions:
 1. If the category_id of each product in the "Product" table matches with the "id" column of the "Product_category" uniquely.
 2. If the above condition is true, then we can say each product has a valid category assigned to it.
 3. If the above condition is false, then the assigned product category is not valid.
