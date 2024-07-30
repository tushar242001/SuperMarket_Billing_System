# Supermarket Billing System

## Description
The Supermarket Billing System is a console-based application developed in C++ to manage the basic operations of a supermarket. The system allows administrators to add, modify, and delete products, while buyers can purchase products and generate receipts.

## Features
- **Administrator Menu:**
  - **Add Product:** Allows administrators to add new products to the inventory.
  - **Modify Product:** Enables administrators to edit the details of existing products.
  - **Delete Product:** Allows administrators to remove products from the inventory.
  - **Back to Main Menu:** Navigate back to the main menu.
- **Buyer Menu:**
  - **Buy Product:** Buyers can select products and quantities to purchase, and generate a receipt.
  - **Go Back:** Navigate back to the main menu.

## Classes and Functions

### Class: `shopping`
- **Private Members:**
  - `int pcode`: Product code
  - `float price`: Product price
  - `float dis`: Discount on the product
  - `string pname`: Product name

- **Public Member Functions:**
  - `void menu()`: Displays the main menu for administrator or buyer login.
  - `void administrator()`: Displays the administrator menu.
  - `void buyer()`: Displays the buyer menu.
  - `void add()`: Allows the administrator to add new products.
  - `void edit()`: Allows the administrator to modify existing products.
  - `void rem()`: Allows the administrator to remove products from the inventory.
  - `void list()`: Lists all the products in the inventory.
  - `void receipt()`: Generates and displays the receipt for the buyer.

## How to Use

1. **Administrator Login:**
   - Use the following credentials to log in as an administrator:
     - Email: `tushar@email.com`
     - Password: `Tushar@123`
   - Once logged in, you can add, modify, or delete products.

2. **Buyer:**
   - Select the "Buyer" option from the main menu.
   - Choose the products and quantities you want to purchase.
   - A receipt will be generated displaying the product details, quantities, and total amount with discounts applied.

## Files
- **`main.cpp`**: Contains the source code for the Supermarket Billing System.
- **`database.txt`**: Stores the product details including product code, name, price, and discount.

## Sample Output

### Main Menu
| 1) Administrator |
| |
| 2) Buyer |
| |
| 3) Exit |

### Administrator Menu
Administrator menu
|1) Add the product|
| |
|___2) Modify the product|
| |
|___3) Delete the product|
| |
|__4) Back to main menu|

### Buyer Menu
1. Buy product
2. Go back

### Adding a Product
Add new product
Product code of the product: 101
Name of the product: Milk
Price of the product: 1.5
Discount on product: 10
Record inserted!

### Receipt Generation
RECEIPT____
Product Num. Product Name Quantity Price Amount Amount with discount
101           Milk           2      1.5    3.0       2.7
Total Amount : 2.7

## Development Environment
- **Language:** C++
- **IDE:** Any C++ IDE (e.g., Code::Blocks, Visual Studio, etc.)

## Future Enhancements
- Implement a graphical user interface (GUI).
- Add user authentication for multiple administrators.
- Enhance error handling and input validation.

## Author
 Tushar Adling
