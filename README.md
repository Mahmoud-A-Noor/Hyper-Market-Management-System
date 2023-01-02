# Hyper Market Management System

## Requirements

- JDK
- Xampp

## Usage

1. Setup JDK 14.0.2 (other versions may also work)
2. Setup Xampp
    1. Run Apache server
    2. Run mySQL server
    3. Open mySQL admin page (phpMyAdmin)
        1. Create database with name **market**
        2. Import the database file **market.sql** provided in the dependencies folder

## Modules

every module has it's own default username and password

![login](https://user-images.githubusercontent.com/59361888/210212787-b5d5bf87-96b9-452a-9991-82e47604b4d3.png)

### Administration Module

**username:** admin <br>
**password:** admin

- Admin has username and password and can alter them.
- Admin manages employees (Add - set unique id, password and type to new employee, Delete, update, List and search all Employees, ).

![admin](https://user-images.githubusercontent.com/59361888/210212808-a99e7b3e-6b8e-498a-bcca-2b53a2fdf223.png)

### Marketing Module

**username:** marketing <br>
**password:** marketing

- Marketing employees can make reports about products (make queries).
- Marketing employees make special offers and send them to inventory management.

![marketing](https://user-images.githubusercontent.com/59361888/210212823-7509f680-d807-4322-97c3-b15ba9b8027b.png)

### Inventory Module

**username:** inventory <br>
**password:** inventory

- Inventory employees (Add, Delete, Update, List, Search) Products.
- System Must send notification when amount of product reduces at special range -set by inventory employees- OR when expiry date of product gets close.
- Manage the Damages items and sales Return.

![inventory](https://user-images.githubusercontent.com/59361888/210212843-192e5332-99c8-4541-b6d4-e6616f2a37fc.png)

### Sales Module

**username:** sales <br>
**password:** sales

- Seller can (search for product, list all products, make and cancel order or cancel part of the order).

![seles](https://user-images.githubusercontent.com/59361888/210212875-83859c51-224c-406a-aeee-6f74c30cf204.png)
![sales](https://user-images.githubusercontent.com/59361888/210212884-f773ef0f-cae3-45d1-ad4d-3c26a176f0c4.png)

