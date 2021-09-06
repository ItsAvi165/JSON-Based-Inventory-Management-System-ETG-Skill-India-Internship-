# JSON-Based-Inventory-Management-System-ETG-Skill-India-Internship-
This Repository contains codes with JSON files for making an Inventory Management System using Python which I have made during my ETG AI/ML Internship.

# I've made an inventory management system which works on NoSQL based dataset.
1. I have two JSON files, 'record' and 'sales'.
2. New Products can be added in inventory which get updated in 'record.json' file.
3. Customer can purchase products and after purchase inventory will get updated in 'record.json'.
4. All the information related to sales will be updated in 'sales.json'.
5. When a customer purchases any item, it is checked whether the item matches the product Id or not.
6. If the quantity of a product that the customer wants to purchase exceeds the available quantity, approprite message is displayed and the purchase can't be made.
7. Total Bill amount is generated based on the purchases made.
8. Each transaction made by the customer is updated accordingly to the 'sales.json' file.
9. Each transactions displays the product Id, quantity purchased and total bill amount.

## Attributes for Product :
* Product name
* Price
* Quantity
* Date of Manufacture
* Date of Expiry

## Features :
* Add Items to the Inventory
* Update the Inventory after adding items
* Customers can purchase products from the Inventory
* Update Inventory after purchase
* Generate the total Bill
* Display total number of transactions and details
