# 🌿 Agro Market - Smart Agricultural E-Commerce Platform

Agro Market is a full-stack web-based agricultural marketplace that connects buyers and sellers in a structured and efficient system.  
It includes **multi-role access, dynamic pricing, product listing, seller dashboard, and complete order management system**.

Built using **HTML, CSS, JavaScript, PHP, and MySQL**.

---

## 🚀 Project Overview

This project simulates a real-world agricultural e-commerce platform where users can browse products, manage carts, place orders, and sellers can manage products dynamically through a dashboard.

The system is designed to handle **role-based access and smart product lifecycle management**.

---

## 🛠️ Tech Stack

- 🌐 HTML 
- 🎨 CSS 
- ⚙️ JavaScript  
- 🐘 PHP  
- 🗄️ MySQL  

---

## ✨ Key Features

### 🛍️ Product Listing System
- Dynamic product display from database  
- Clean and user-friendly interface  
- Product images, price, and details shown clearly  

---

### 📦 Order Management System
- Add to cart and place orders  
- Orders stored in MySQL database  
- Full flow: Product → Cart → Checkout → Order Confirmation  
- Order tracking support  

---

### 👨‍🌾 Seller Dashboard
- Seller can add new products  
- Update and delete existing products  
- Manage stock and pricing  
- View customer orders  

---

### 💰 Dynamic Pricing System (Smart Logic)
Products automatically change price and status based on time:

- 🟢 **0–2 days** → Full price (Fresh product)  
- 🟡 **3–5 days** → Discount applied automatically  
- 🔴 **7+ days** → Product marked as expired  
  - Expired products are automatically hidden or image removed  
  - Prevents outdated items from showing in listings  

---

### 👥 Multi-Role System
- 👨‍💼 Admin: Controls system and users  
- 👨‍🌾 Seller: Manages products and orders  
- 🛒 Customer: Browses, carts, and places orders  

---

## 📁 Project Structure
AgroMarket/
├── api/                    
│   ├── admin.php
│   ├── auth.php
│   ├── cart.php
│   ├── config.php          
│   ├── orders.php
│   ├── products.php
│   ├── reviews.php
│   └── upload.php
├── database/
│   └── agromarketbd.sql    
├── images/                 
│   ├── bkash.png
│   ├── Nagad.png
│   └── rocket.png
├── .htaccess
├── app.js
├── index.html
├── login.html
├── products.html
├── product-details.html
├── cart.html
├── checkout.html
├── consumer-dashboard.html
├── consumer-orders.html
├── farmer-dashboard.html
├── farmer-add-product.html
├── farmer-products.html
└── admin-dashboard.html
|__ register.html
|___styles.css

## 🔄 System Workflow

1. Seller adds products via dashboard  
2. Products appear in listing page  
3. Customer browses products  
4. Adds items to cart  
5. Proceeds to checkout  
6. Places order  
7. System updates database  
8. Seller/admin manage orders  

---

## 👨‍💻 My Contribution

I contributed to the core development of this project, including:

### 🛒 Cart System
- Implemented add-to-cart functionality using PHP & JavaScript  
- Managed cart session and item updates  

### 📦 Order Management System
- Built complete order placement system  
- Stored and retrieved orders from MySQL database  

### 👨‍🌾 Seller Dashboard
- Designed seller interface for product management  
- Enabled CRUD operations for products  


### 🌐 Frontend & Backend Integration
- Built responsive UI using HTML & CSS  
- Connected PHP backend with MySQL database  
- Ensured smooth system workflow  

---

## 📌 Future Improvements
 
- 📱 Fully responsive mobile UI  
- 🔔 Real-time order notifications  
- 📊 Admin analytics dashboard  
   

---


---

## 📜 License

This project is for educational purposes only.

---

## ⭐ Acknowledgements

Thanks to everyone who supported this project development.

---

