
# Shopping mart

The code is an inventory management system with user and admin functionalities. It includes features such as viewing available items, placing orders, generating bills with discounts, and admin controls for managing quantities, prices, sales reports, and user credentials.

Here's a brief overview of the main functionalities:

Struct Definition:
struct product is defined to store information about each product, including name, quantity (q), price (p), quantity sold (sq), total quantity (tq), and total sales price (sp).

Global Variables:
Arrays and variables are declared globally, including an array of products (p[50]), user credentials (AUserName, APass), and user input variables (UserName, Pass).

Product Initialization:
The code initializes an array of products with names, prices, and initial quantities.

User Interface:
The user is presented with a main menu allowing them to choose between user and admin modes or exit the software.

User Mode:
Users can view available items, receive order instructions, place orders, and receive bills with discounts based on the total amount spent.

Admin Mode:
Admins can log in with a username and password.
Admins have access to various functionalities, including viewing product quantities and prices, updating quantities and prices, viewing sales reports, adding new products, and changing login credentials.

Stock Alert:
The code checks for low stock and displays a stock alert if any product quantity is below a certain threshold.

Looping and Program Flow:
The program is structured using loops to keep the user interacting with the system until they choose to exit.
