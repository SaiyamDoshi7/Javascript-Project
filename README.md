# JavaScript CRUD & Cart Project – README

# PROJECT TITLE : GLOWING SKIN

## 🚀 Project Overview

This is a **JavaScript-based Skin Care E‑Commerce Mini Project** where users can:

* Add new products
* Edit existing products
* Delete products
* View product details
* Add items to cart
* Increase/decrease quantity
* View dynamic grand total

It is built using **pure HTML, CSS, and JavaScript** without any frameworks.

---

## 📂 Project Folder Structure

```
Js-Project/
│
├── index.html
├── add_product.html
├── edit.html
├── cart.html
├── view.html
├── product_details.html
│
├── Screenshots/
|   ├── Index.png
|   ├── Add_Product.png
|   ├── Edit_Product.png
|   ├── View_Product.png
|   ├── Shopping_Cart.png
|   └── Product_Details.png
|
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
│       └── (all product and UI images)
```

---

## ✨ Features

### 🛍️ Product Management (CRUD)

* **Create:** Add new product with name, price, image, and description
* **Read:** View all products on homepage and view.html
* **Update:** Edit product details in edit.html
* **Delete:** Remove product from list

### 🛒 Add to Cart System

* Add any product to cart from **product listing** or **product details** page
* Increase or decrease quantity with **+ / − buttons**
* Remove item from cart
* Auto-update **grand total**

### 📱 Responsive Design

* Simple, clean, mobile-friendly UI
* Uses pure CSS (no Bootstrap)

---

## ⚙️ How It Works

### 1️⃣ Adding a Product

User fills a form → data stored in `localStorage`

### 2️⃣ Editing a Product

User selects a product → data loads into edit form → updated in localStorage

### 3️⃣ Viewing Products

index.html & view.html read all stored products and display cards dynamically

### 4️⃣ Cart Operations

Cart detail stored in localStorage:

* Add product
* Increase quantity
* Decrease quantity
* Remove product
* Update total

---

## ▶️ How to Run the Project

1. Download the entire **Js-Project** folder
2. Open **index.html** in any browser
3. That’s it — the whole project runs locally!

*(No server, no installation required)*

---

## 🖼️ Screenshots

### 📌 Homepage (Index)

```
![Homepage](./Screenshots/Index.png)
```

### 📌 Add Product Page

```
![Add Product](./Screenshots/Add_Product.png)
```

### 📌 Edit Product Page

```
![Edit Product](./Screenshots/Edit_Product.png)
```

### 📌 View Products

```
![View Products](./Screenshots/View_Product.png)
```

### 📌 Shopping Cart Page

```
![Cart Page](./Screenshots/Shopping_Cart.png)
```
### 📌 Product Details Page

```
![Deatils Page](./Screenshots/Product_Details.png)
```

---

## 🤝 Contributing

If you want to improve this project, feel free to:

* Fix bugs
* Add new features
* Improve UI/UX
* Optimize JavaScript code

Just follow these steps:

1. Fork the project
2. Make your changes
3. Submit a pull request

---

## 🙌 Acknowledgements

This project was created as part of a JavaScript practice assignment focusing on CRUD operations and cart functionality.

---
