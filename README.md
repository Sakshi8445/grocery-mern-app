# 🛒 Grocery MERN App

A full-stack grocery shopping web application built with the MERN stack. Users can browse products, manage their cart and place orders, while sellers can manage their own products and orders.

## ✨ Features

- User registration and login with authentication
- Browse products by category
- Add to cart and update quantities
- Save delivery addresses
- Place and track orders
- Seller panel to add, edit and manage products
- Product image upload
- Responsive design

## 🛠 Tech Stack

**Frontend:** React, Vite, Tailwind CSS  
**Backend:** Node.js, Express.js  
**Database:** MongoDB, Mongoose  
**Other:** JWT authentication, Multer (image upload)

## 📁 Project Structure

```
grocery-mern-app
├── client        # React frontend
└── backend       # Node + Express API
    ├── config
    ├── controller
    ├── middlewares
    ├── models
    └── routes
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Sakshi8445/grocery-mern-app.git
cd grocery-mern-app
```

### 2. Setup backend

```bash
cd backend
npm install
```

Create a `.env` file inside `backend` and add:

```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

Start the server:

```bash
npm start
```

### 3. Setup frontend

```bash
cd client
npm install
npm run dev
```

The app will run on `http://localhost:5173`.

## 📸 Screenshots

_Add screenshots here_

## 👩‍💻 Author

**Sakshi Dhall**  
GitHub: [@Sakshi8445](https://github.com/Sakshi8445)
