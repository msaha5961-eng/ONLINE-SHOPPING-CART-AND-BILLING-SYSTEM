# ONLINE-SHOPPING-CART-AND-BILLING-SYSTEM

## Project Overview
The Online Shopping Cart and Billing System is a Python-based application designed to simulate an online shopping platform. It allows users to browse products, add items to a shopping cart, modify their cart, and generate a final bill based on the selected items.

This project demonstrates the implementation of basic programming concepts such as data structures, functions, file handling, and object-oriented programming to create a simple and efficient shopping experience.

---

## Features
- Display available products with their prices
- Add products to the shopping cart
- Remove items from the cart
- Update product quantity
- Calculate total price automatically
- Generate a detailed bill/invoice
- Apply basic billing calculations
- Store and manage product information
- User-friendly menu-driven interface

---

## Concepts Used
- Python Basics
- Variables and Data Types
- Conditional Statements (`if-else`)
- Loops (`for`, `while`)
- Functions
- Lists and Dictionaries
- Object-Oriented Programming (Classes and Objects)
- File Handling
- Exception Handling

---

## Technologies Used
- **Programming Language:** Python
- **Development Environment:** VS Code / Jupyter Notebook
- **Data Storage:** File Handling (Text Files)
- **Version Control:** Git & GitHub

---

## How It Works
1. The program displays a list of available products along with their prices.
2. The user selects products and adds them to the shopping cart.
3. The cart stores the selected items and their quantities.
4. Users can update or remove items before checkout.
5. The system calculates the total amount based on the cart items.
6. A final bill is generated showing the purchased items, quantities, and total cost.

---

## 📸 Sample Output

```text
====== ONLINE SHOPPING CART ======

Enter Customer Name: Moumita

1. View Products
2. Add Product to Cart
3. View Cart
4. Generate Bill
5. Exit

Enter your choice: 1

========== PRODUCT CATALOG ==========
ID   Product         Price      Stock
---------------------------------------------
1    Rice            ₹60        10
2    Sugar           ₹50        8
3    Milk            ₹35        15
4    Bread           ₹40        10
5    Coffee          ₹180       6
6    Biscuits        ₹30        20
---------------------------------------------

Enter your choice: 2

Enter Product ID: 1
Enter Quantity: 2

Rice added to cart successfully!

Enter your choice: 2

Enter Product ID: 3
Enter Quantity: 1

Milk added to cart successfully!

Enter your choice: 3

========== YOUR CART ==========
Product         Price      Qty      Total
--------------------------------------------------
Rice            ₹60        2        ₹120
Milk            ₹35        1        ₹35
--------------------------------------------------
Subtotal: ₹155

Enter your choice: 4

========== SHOPPING BILL ==========
Customer : Moumita

----------------------------------------
Product         Qty       Amount
----------------------------------------
Rice            2         ₹120
Milk            1         ₹35
----------------------------------------
Subtotal      : ₹155.00
GST (5%)      : ₹7.75
Grand Total   : ₹162.75
========================================

Bill saved successfully in bill.txt

Thank you for shopping!
```

## Limitations
- No graphical user interface (GUI)
- Payment gateway is not integrated
- Product database is limited
- Does not support multiple users
- Uses basic file storage instead of a database

---

## Future Improvements
- Add GUI using Tkinter/PyQt
- Integrate online payment options
- Use SQL database for product and user management
- Add user authentication and login system
- Develop it into a web-based shopping application

---

## Conclusion
The Online Shopping Cart and Billing System is a beginner-friendly Python project that provides practical understanding of programming concepts and real-world application development. It helps in learning how shopping systems work by implementing product management, cart operations, and automated billing.
