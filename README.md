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

## 📁 Project Folder Structure

ecom/
├── backend/ # Express API & server-side code
│   ├── config/         # Database configuration (e.g., MongoDB)
│   ├── controllers/    # Controllers for users, products, orders
│   ├── data/           # Sample data files (products.js, users.js)
│   ├── middleware/     # Custom middleware (auth, error handling)
│   ├── models/         # Mongoose models (User, Product, Order)
│   ├── routes/         # API route files (productRoutes, userRoutes, etc.)
│   ├── utils/          # Utility functions (e.g., JWT token generator)
│   ├── seeder.js       # Script to seed the database
│   └── server.js       # Main server entry point (Express setup)
│
├── frontend/           # React client app
│   ├── public/         # Static assets (index.html, favicon, etc.)
│   └── src/            # React app source code
│       ├── actions/        # Redux actions
│       ├── components/     # Reusable components (Header, Footer, etc.)
│       ├── constants/      # Redux constants
│       ├── reducers/       # Redux reducers
│       ├── screens/        # Page components (HomeScreen, CartScreen, etc.)
│       ├── store.js        # Redux store configuration
│       └── App.js          # Main React App component
│
├── uploads/            # Uploaded product images (via multer)
├── package.json        # Project-level scripts and dependencies
├── Procfile            # Deployment configuration (for Heroku/Render)
├── .gitignore          # Git ignored files/folders
└── README.md           # Project documentation


