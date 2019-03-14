# bamazon
 MySQL Amazon-like storefront
Overview
Bamazon is  an Amazon-like storefront that function via  MySQL. The app will take in orders from customers and deplete stock from the store's inventory.


Create a MySQL Database called bamazon. Add a  products table and define product names, departments, price, and stock quantity. Populate this database with around 10 different products. (i.e. Insert "mock" data rows into this database and table).
![database](./images/database.png)


Then create a Node application called bamazonCustomer.js. Running this application will first display all of the items available for sale. Include the ids, names, and prices of products for sale.
The app should then prompt users with two messages.

The first should ask them the ID of the product they would like to buy.
![item](./images/what_is_item_id.png)


The second message should ask how many units of the product they would like to buy.
![item](./images/how_many_buy.png)


Once the customer has placed the order, your application should check if your store has enough of the product to meet the customer's request.

If not, the app should log a phrase like Insufficient quantity!, and then prevent the order from going through.

![item](./images/insufficient_order.png)

However, if your store does have enough of the product, you should fulfill the customer's order.

This means updating the SQL database to reflect the remaining quantity.
Once the update goes through, show the customer the total cost of their purchase.
![item](./images/order_placed_sucess.png)



[![video](https://youtu.be/8i1PK7M815U)](
