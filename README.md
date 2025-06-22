# 🛒 ProShop eCommerce Platform

## 📖 Description

**ProShop** is a full-featured eCommerce platform built with the powerful **MERN stack** and **Redux**.  
It allows users to browse products, add them to a cart, make purchases, review and rate products, and manage their profiles.  
Admin users can manage products, users, and orders. The platform integrates with **PayPal** for secure payments

---

## ✨ Features

- 🛍️ **Shopping Cart**: Add, update, and remove products from your cart  
- ⭐ **Product Reviews & Ratings**: Leave feedback and rate products  
- 🎠 **Top Products Carousel**: Highlight best-selling products  
- 🔍 **Product Search & Pagination**: Easily find and browse products  
- 👤 **User Profiles**: View order history and update profile info  
- 🛠️ **Admin Dashboard**: Manage products, users, and orders  
- 🚚 **Order Management**: Mark orders as delivered  
- 💳 **Checkout Process**: Shipping, payment, and order summary  
- 🅿️ **PayPal Integration**: Secure payment gateway  
- 🌱 **Database Seeder**: Populate products & users for testing  

---

## 🛠️ Tech Stack

### Frontend
- ⚛️ React  
- 🛡️ Redux  
- 🎨 React Bootstrap  
- 🛣️ React Router  
- 🧰 Axios  

### Backend
- 🟢 Node.js  
- 🚂 Express.js  
- 🗄️ MongoDB & Mongoose  
- 🔐 JWT Authentication  
- 📦 Multer (file uploads)  
- 💳 PayPal API  

---

## 📁 Folder Structure
ecom/
├── backend/ # Express API & server-side code
│ ├── config/ # Database config
│ ├── controllers/ # Route controllers (user, product, order)
│ ├── data/ # Sample data for seeding
│ ├── middleware/ # Auth & error handling middleware
│ ├── models/ # Mongoose models (User, Product, Order)
│ ├── routes/ # API route definitions
│ ├── utils/ # Utility functions (e.g., JWT token)
│ ├── seeder.js # Database seeder script
│ └── server.js # Main server file
│
├── frontend/ # React client app
│ ├── public/ # Static assets (images, favicon, etc.)
│ └── src/ # Source code
│ ├── actions/ # Redux actions
│ ├── components/ # Reusable UI components
│ ├── constants/ # Redux constants
│ ├── reducers/ # Redux reducers
│ ├── screens/ # Page components (Home, Cart, Admin, etc.)
│ ├── store.js # Redux store setup
│ └── App.js # Main app component
│
├── uploads/ # Uploaded product images
│
├── package.json # Project scripts and dependencies
├── Procfile # Deployment process file (Heroku/Render)
├── .gitignore # Files/folders to ignore in git
└── README.md # Project documentation


