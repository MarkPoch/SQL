Computer Store Database
The Computer Store Database is a relational database that stores information about various computer components and accessories available in a computer store. It is designed to manage the inventory, prices, quantities, and installation times of these items. The database consists of a single table called "computer_store."

Table Structure
The "computer_store" table has the following columns:

id: An integer column representing the unique identifier for each item in the store.
Component: A text column containing the name or description of the computer component or accessory.
Price: An integer column representing the price of the item in the store.
Quantity: An integer column indicating the available quantity of the item.
Install_time: An integer column specifying the estimated installation time required for the item.
Example Data
The database includes example data for several items available in the computer store. Each row represents a distinct item, including its component name, price, quantity, and installation time. Here is a sample of the data:

id	Component	Price	Quantity	Install_time
1	Graphics Card	499.99	10	30
2	CPU	399.99	14	45
3	MotherBoard	599.99	12	15
4	Storage	199.99	75	5
5	Ram	355.99	105	7
...	...	...	...	...
Query Example
The database query provided demonstrates how to retrieve specific items from the "computer_store" table. In this example, it retrieves items with an installation time less than 30, sorted by price in ascending order.


SELECT * 
FROM computer_store
WHERE Install_time < 30
ORDER BY price;
This query will return a result set with the items that meet the specified criteria.

This database can be utilized by a computer store to track inventory, manage pricing, and estimate installation times for various computer components and accessories. It provides a convenient way to organize and access information related to the store's products.