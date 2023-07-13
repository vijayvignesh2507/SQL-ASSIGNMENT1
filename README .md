# SQL-ASSIGNMENT-1
# SQL Schema README

This README file provides an overview of the SQL schema containing entities such as `Customer`, `Purchase`, `Inventory`, `Region`, and `Product`. Additionally, it includes an Entity-Relationship (ER) diagram illustrating the relationships between these entities.

Entity Descriptions

Customer
The `Customer` entity represents individuals or entities who make purchases. It includes attributes such as `customer_id`, `name`, `email`, `phone`, `address`, and any other relevant information about the customer.

Purchase
The `Purchase` entity represents a specific transaction made by a customer. It includes attributes such as `purchase_id`, `customer_id` (foreign key to `Customer` entity), `product_id` (foreign key to `Product` entity), `quantity`, `price`, and `timestamp` (to record the time of purchase).

Inventory
The `Inventory` entity represents the stock or availability of products. It includes attributes such as `product_id` (foreign key to `Product` entity), `quantity`, `price`, and any other relevant information about the product inventory.

Region
The `Region` entity represents a geographical region or location. It includes attributes such as `region_id` and `region_name`, which can be used to categorize customers or products based on their respective regions.

Product
The `Product` entity represents individual items available for purchase. It includes attributes such as `product_id`, `name`, `description`, `category`, and `price`.

Entity-Relationship (ER) Diagram:

The following diagram depicts the relationships between the entities in the SQL schema:

![image](https://github.com/Nivas2003/SQL-ASSIGNMENT-1/assets/112155795/03a3d416-6724-44ec-8096-d1666a5218cf)


