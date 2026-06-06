# 🍔 Foodie - Food Delivery Web Application

Foodie is a full-stack food delivery platform built using the MERN stack. Users can browse food items, add products to their cart, place orders, and make online payments, while administrators can manage food items and track customer orders through a dedicated admin dashboard.

## 🚀 Features

### User Features

* User registration and login
* JWT-based authentication
* Browse food menu by category
* Add and remove items from cart
* Place food orders
* Online payment integration
* View order history
* Responsive UI for desktop and mobile devices

### Admin Features

* Secure admin login
* Add new food items
* Upload food images
* View all food items
* Remove food items
* Manage customer orders
* Update order status

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* CSS3
* Axios
* React Router

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Bcrypt

### Deployment

* Frontend: Vercel
* Backend: Render
* Database: MongoDB Atlas

## 📂 Project Structure

```text
Foodie
├── frontend      # Customer-facing application
├── admin         # Admin dashboard
└── backend       # Express API and database logic
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Shreyansh0100/Foodie.git
cd Foodie
```

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file:

```env
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```

Run backend:

```bash
npm run server
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Admin Setup

```bash
cd admin
npm install
npm run dev
```

## 🔒 Authentication

Foodie uses JWT-based authentication to secure user sessions and protect private routes.

## 📸 Screenshots

Add screenshots of:

* Home Page
* Food Menu
* Cart Page
* Order Page
* Admin Dashboard

## 🌟 Future Improvements

* Real-time order tracking
* Email notifications
* Cloudinary image storage
* User profile management
* Recommendation system
* Coupon and discount support

## 👨‍💻 Author

Shreyansh Singh

GitHub: https://github.com/Shreyansh0100
