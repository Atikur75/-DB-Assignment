Question 1: 

    The relationship between the “Product” and “Product_Category” entities have a one-to-many relationship. 

	Here each “product_category” has multiple “product” associated with it.
	Each “product” belongs to one specific “product_category”. 
	Here, the relationship is established through the “category_id” field in the “product” 
	model which references the “id” field of the “product_category” model. 

Question 2:

    Through foreign key constraints I can ensure that each product in the “product” table has a valid category assigned to it. 
    The “category_id” field in the “product” table contains foreign key which referencing the “id” field of the “product_category” table. 
    This helps in maintaining referential integrity, ensuring that each product’s category ID corresponds to a valid category ID in the “product_category” table. 
