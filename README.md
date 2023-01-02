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

![login.PNG](https://github.com/Mahmoud-A-Noor/Hyper-Market-Management-System/blob/main/dependencies/previews/login.png?raw=true)

### Administration Module

**username:** admin <br>
**password:** admin

- Admin has username and password and can alter them.
- Admin manages employees (Add - set unique id, password and type to new employee, Delete, update, List and search all Employees, ).

![admin.PNG](dependencies/previews/admin.png)

### Marketing Module

**username:** marketing <br>
**password:** marketing

- Marketing employees can make reports about products (make queries).
- Marketing employees make special offers and send them to inventory management.

![marketing.PNG](dependencies/previews/marketing.png)

### Inventory Module

**username:** inventory <br>
**password:** inventory

- Inventory employees (Add, Delete, Update, List, Search) Products.
- System Must send notification when amount of product reduces at special range -set by inventory employees- OR when expiry date of product gets close.
- Manage the Damages items and sales Return.

![inventory.PNG](dependencies/previews/inventory.png)

### Sales Module

**username:** sales <br>
**password:** sales

- Seller can (search for product, list all products, make and cancel order or cancel part of the order).

![seller.PNG](dependencies/previews/seller.png)

![seller-previous.PNG](dependencies/previews/seller-previous.png)
