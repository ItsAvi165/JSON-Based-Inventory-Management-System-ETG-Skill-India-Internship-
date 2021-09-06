# JSON-Based-Inventory-Management-System-ETG-Skill-India-Internship-
This Repository contains codes with JSON files for making an Inventory Management System using Python which I have made during my ETG AI/ML Internship.

# I've made an inventory management system which works on NoSQL based dataset.
1. I have two JSON files, 'record' and 'sales'.
2. New Products can be added and simultaneously get updated in 'record.json'
3. Purchasing items can be done by the customer and simultaneously get updated in 'record.json'and 'sales.json'
4. When a customer purchase any item, it is checked whether the item matches the product Id or not
5. If the quantity of a product that the customer wants to purchase exceeds the originally available quantity, approprite message is displayed and the purchase can't be made
6. Total Bill amount is generated based on the purchases made
7. Each transaction made by the customer is updated accordingly to the 'sales.json' file
8. Each transactions display the product Id, quantity purchased and total bill amount.

## Attributes for Product :
* Product name
* Price
* Quantity
* Date of Manufacture
* Date of Expiry

## Features :
* Add Items to the Inventory
* Update the Inventory after adding items
* Purchaing items by Customers from the Inventory
* Update Inventory after purchase
* Generate the total Bill
* Display total number of transactions
