# 🛒 E-Commerce MERN App

This is a fully-featured E-Commerce demo application showcasing a modern tech stack with MongoDB, Redis, Stripe, and JWT-based authentication.

## 📚 About This Project

Here are the core features:

- 🚀 **Project Setup**
- 🗄️ **MongoDB & Redis Integration**
- 💳 **Stripe Payment Setup**
- 🔐 **Robust Authentication System** with JWT (Access/Refresh Tokens)
- 📝 **User Signup & Login**
- 🛒 **E-Commerce Core** (Product Listings, Category Management)
- 📦 **Product & Category Management**
- 🛍️ **Shopping Cart Functionality**
- 💰 **Checkout** with Stripe
- 🏷️ **Coupon Code System**
- 👑 **Admin Dashboard** for product and order management
- 📊 **Sales Analytics** for tracking performance
- 🎨 **UI Design** with Tailwind CSS
- 🛒 **Cart & Checkout Process**
- 🔒 **Security & Data Protection**
- 🛡️ **Caching** with Redis

---

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Redis
- **Payment Processing**: Stripe
- **Authentication**: JWT (Access & Refresh Tokens)
- **UI/UX**: Tailwind CSS
- **Frontend**: React (optional)
- **Cloud Storage**: Cloudinary for images

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/ecommerce-store-demo.git
cd ecommerce-store-demo
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Setup the `.env` File

Create a `.env` file in the root directory and add the following:

```bash
PORT=5000
MONGO_URI=your_mongo_uri
UPSTASH_REDIS_URL=your_redis_url
ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
NODE_ENV=development
```

### 4. Build the Project
```bash
npm run build
```

### 5. Run the App Locally
```bash
npm run start
```

### 6. Access the App

Visit `http://localhost:5000` in your browser to view the application.

---

## ⚙️ Features

- **User Authentication**: Secure signup, login, and JWT-based access/refresh token system.
- **Product Management**: Easily manage products and categories through the admin dashboard.
- **Shopping Cart**: Add, edit, and remove items from the cart, and proceed to checkout.
- **Payment**: Seamless Stripe payment integration with real-time order processing.
- **Coupon Codes**: Apply discount codes at checkout.
- **Sales Analytics**: Visualize sales data and gain insights into product performance.
- **Responsive Design**: Optimized for all devices using Tailwind CSS.
- **Caching with Redis**: Boost performance and improve the user experience.

---

## 🛠️ Build & Deployment

This app is designed to be scalable and can be deployed on platforms like Heroku, Vercel, or AWS. Follow the steps in the course to deploy your application.

---

## 🛡️ Security

This project implements:

- **JWT Tokens** for secure authentication.
- **Data Encryption** for sensitive data.
- **API Protection** with proper rate limiting and validation.
