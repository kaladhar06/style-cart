# 🛍️ StyleCart – Clothing E-Commerce Application

StyleCart is a **Python-based clothing e-commerce application** designed for **Men's and Women's clothing**. The project provides separate **Admin and User modules** to manage products, shopping carts, and orders.

The project is developed using Python with **JSON files for data storage**. It focuses on implementing the basic functionality of an online clothing store in a simple and easy-to-understand way.

---

## 📌 Project Overview

StyleCart provides two main modules:

### 👨‍💼 Admin Module

The Admin can manage the products and view customer orders.

Admin features include:

* Admin Login
* Add Products
* View Products
* Update Products
* Delete Products
* View Customer Orders

### 👤 User Module

Users can create an account, browse clothing products, manage their cart, and place orders.

User features include:

* User Registration
* User Login
* Browse Men's Clothing
* Browse Women's Clothing
* View Product Details
* Add Products to Cart
* View Cart
* Update Cart Quantity
* Remove Products from Cart
* Checkout and Place Orders
* View My Orders

---

## ✨ Key Features

### 🔐 Authentication

* Separate Admin and User login systems
* User registration functionality
* Basic username and password validation

### 👕 Product Management

* Add new clothing products
* View available products
* Update product name, price, size, and stock
* Delete products
* Products are categorized into Men's and Women's clothing

### 🛒 Shopping Cart

* Add products to the cart
* View cart items
* Update product quantity
* Remove products from the cart
* Calculate total cart price

### 📦 Order Management

* Users can place orders through checkout
* Product stock is updated after successful checkout
* Users can view their own orders
* Admin can view customer orders
* Orders have a status such as `Pending`

### 💾 Data Storage

JSON files are used to store:

* Admin credentials
* User information
* Product information
* Order information

---

## 🛠️ Technologies Used

* **Python**
* **JSON**
* Python Functions
* Python Modules
* File Handling

---

## 📂 Project Structure

```text
StyleCart/
│
├── admin/
│   ├── main.py
│   ├── Alogin.py
│   ├── Aaddproduct.py
│   ├── Aviewproduct.py
│   ├── Aupdateproduct.py
│   ├── Adeleteproduct.py
│   └── Aorders.py
│
├── user/
│   ├── Umain.py
│   ├── Uregister.py
│   ├── Ulogin.py
│   ├── Uviewproduct.py
│   ├── Uproductdetails.py
│   ├── Ucart.py
│   ├── Ucartremove.py
│   ├── Ucartupdate.py
│   ├── Ucheckout.py
│   └── Uorders.py
│
└── data/
    ├── admin.json
    ├── users.json
    ├── products.json
    └── orders.json
```

---

## ⚙️ How to Run the Project

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
```

### 2. Open the Project Folder

```bash
cd StyleCart
```

### 3. Run the User Module

Open the terminal inside the `user` folder:

```bash
cd user
python Umain.py
```

The User menu will appear:

```text
===== StyleCart =====

Welcome to StyleCart!

1. Men's Clothing
2. Women's Clothing
3. Product Details
4. Add to Cart
5. View Cart
6. Remove from Cart
7. Update Cart
8. Checkout
9. My Orders
10. Logout
```

### 4. Run the Admin Module

Open another terminal and navigate to the `admin` folder:

```bash
cd admin
python main.py
```

The Admin login screen will appear:

```text
===== StyleCart Admin Login =====

Enter username:
Enter password:
```

---

## 🔑 Admin Login

For the demo version, the default admin credentials are:

```text
Username: admin
Password: admin123
```

> **Note:** These credentials are for the demo project only. In a real-world application, passwords should be securely hashed and not stored as plain text.

---

## 🔄 Application Flow

### Admin Flow

```text
Admin Login
     ↓
Admin Dashboard
     ↓
Manage Products
     ↓
Add / View / Update / Delete
     ↓
View Orders
```

### User Flow

```text
Register
   ↓
Login
   ↓
Browse Products
   ↓
View Product Details
   ↓
Add to Cart
   ↓
Update / Remove Cart Items
   ↓
Checkout
   ↓
Place Order
   ↓
View My Orders
```

---

## 💾 JSON Data Files

The application uses JSON files instead of a database.

### `admin.json`

Stores administrator login details.

### `users.json`

Stores registered user information.

### `products.json`

Stores clothing product details such as:

* Product ID
* Product Name
* Category
* Price
* Size
* Stock Quantity

### `orders.json`

Stores customer order information such as:

* Order ID
* User ID
* Customer Name
* Product
* Quantity
* Price
* Total
* Order Status

---

## 🎯 Project Objectives

The main objectives of StyleCart are:

* To understand the basic structure of an e-commerce application.
* To implement separate Admin and User functionality.
* To practice Python functions and modules.
* To understand file handling using JSON.
* To implement basic product and order management.
* To understand shopping cart and checkout functionality.

---

## 🚀 Future Enhancements

The project can be extended in the future by adding:

* MySQL database integration
* Flask backend
* HTML and CSS frontend
* User password hashing
* Product images
* Search and filter functionality
* Payment integration
* Admin order status management
* User profile management
* Responsive web interface

---

## 👨‍💻 Author

**Kaladhar Reddy**

This project was developed as a learning project to understand **Python, modular programming, file handling, and basic e-commerce application development**.

---

## 📄 License

This project is created for **educational and learning purposes**.
