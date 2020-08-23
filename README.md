# C-OnlineMarathon-Sprint16
C# Online Marathon Sprint 16. EFC
Your task is to create a database according to the schema:
[pict.1]
1.	Create a data model:
•	Define classes: Product, Customer, Supermarket with properties according to schema. Don’t forget about properties appropriate to entities’ Primary keys;
•	Define class Order and OrderDetails with properties according to schema. Don’t forget about navigation properties (future entities’ Foreign keys).
2.	Create context class ShoppingContext and specify which entities are included in the data model: Products, Customers, Supermarkets, Orders, OrderDetails.
3.	Specify the connection service and options of AddDBContext in Startup.cs (ConfigureServices).
4.	Add connection string to appsettings.json.
5.	Create the class for seeding your DataBase (SampleData.cs). Define the ServiceProvider in Program.cs.
6.	Build the application. As the result you might have your DB in SQL Server Object Explorer [pict.2, 3, 4]. 
•	Note. In case of any mistakes in DB schema you are able to alter the models, add migrations and update your database.
7.	Create controllers and views for Products, Supermarkets, Customers DataModels (use scaffolding). Change Index page of application (add navy-bars and links to appropriate Index pages of DataModels) [pict.5]
8.	Add the ability to sort the list of customers by the last name or address (in descending and ascending order) [pict. 6]
9.	Add the ability to filter the list of customers by last or first name according to substring in input field [pict. 7]
10.	Add pagination to Supermarkets index page [pict.8]
11.	Create page Orders that reads and displays related data in the following ways [pict.9]:
•	The list of orders displays related data from the Customers and Supermarkets entities;
•	When the user selects an order, related to it data from OrderDetails entity are displayed;

Note. While the creation of the items in entities that use the navigation properties user is able to see the real names of items (‘product name’ but not a ‘productId’, ‘supermarket name’ but not a ‘supermarketId’, etc).
Useful links:
