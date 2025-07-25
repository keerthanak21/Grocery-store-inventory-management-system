# Grocery-store-inventory-management-system

A simple Grocery Management System built in C that manages sales activity in a supermarket.  
This system helps store product details, handle admin & user operations, manage carts, and calculate bills, all using data from a CSV file.

---

##  **Objective**

The goal of this project is to replace a manual sales record system with software that:
- Reduces paperwork
- Automates calculations
- Makes sales operations fast and user-friendly
- Saves data to and reads from a CSV file

---

##  **Project Description**

The system is divided into two parts:

### Admin
- Login with password (max 3 attempts)
- View all products in each category
- Update product price or quantity
- Delete products from categories

### User
- View products sorted by expiry date
- Search for items
- Add items to shopping cart
- View cart contents
- Delete items from cart
- Checkout to see total bill

Products are stored as a **multi-linked list** based on categories (e.g., Body products, Food products, Cosmetics, Stationery, Kitchen products).  
Each category and product has a unique ID.

---

##  **CSV File Format**

The system reads initial data from a file named `final_csv.csv`.

**Format:**

| PID | IID | NAME | PRICE | EXPDATE | QTY |
|----|-----|------|------:|--------:|---:|
| int | int | string | int | string (dd-mm-yyyy) | int |

### Technologies & Requirements
C Programming Language
CSV file as product database
Standard C libraries: stdio.h, stdlib.h, string.h, time.h

### Features
Login system for admin and users
Category-based product listing
Products sorted by expiry date
Cart management: add, view, delete items
Final bill calculation
Search items by name

### Conclusion
This Supermarket Management System helps replace manual record-keeping, saves time on calculations, and reduces paperwork, making supermarket operations smoother and faster.



