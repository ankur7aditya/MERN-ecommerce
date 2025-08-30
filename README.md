# MERN E-commerce

A full-stack e-commerce platform built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). This project enables users to shop for products online, while providing admins with tools to manage inventory and orders.

---

## Features

### User
- **Product Browsing & Search:** Discover products by category or keyword.
- **Product Reviews:** Write, edit, and delete reviews; update product ratings.
- **Wishlist:** Add/remove products and manage personal wishlists.
- **Order Management:** Place orders and view order history.
- **Profile Management:** Edit user details and manage addresses.
- **Shopping Cart:** Add products, update quantities, and view cart totals.

### Admin
- **Product Management:** Create, update, or delete products; manage stock and pricing.
- **Order Management:** View and update all order statuses.

### Security & Experience
- **Authentication:** Login, registration, OTP verification, password reset, and logout.
- **Secure APIs:** Communication is secured via JWT authentication and data encryption.

---

## Tech Stack

- **Frontend:** React.js, Redux Toolkit, Material UI/TailwindCSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT, bcrypt
- **Others:** RESTful APIs, CORS middleware

---

## Installation

### Prerequisites
- Node.js and npm
- MongoDB (local or use [MongoDB Atlas](https://www.mongodb.com/cloud/atlas))
- React.js

### Steps

#### 1. Clone the Repository
```
git clone https://github.com/ankur7aditya/MERN-ecommerce.git
cd MERN-ecommerce
```

#### 2. Backend Setup
```
cd server
npm install
# Configure your `.env` file with variables such as:
# MONGO_URI=your-mongodb-uri
# JWT_SECRET=your-jwt-secret
npm run start
```

#### 3. Frontend Setup
```
cd client
npm install
npm run start
```
- The client runs at `http://localhost:3000`

---

## Usage

- **User:** Register or log in, shop for products, add items to cart, checkout, and manage orders and profile.
- **Admin:** Manage inventory, users, and orders via the admin dashboard.

---

## Contributing

Contributions are welcome! Fork the repository and submit a pull request for new features, bug fixes, or improvements.

---
