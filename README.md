# E-Commerce Platform - Mini Shop 🚀

This is a full-stack E-Commerce application built using the MERN (MongoDB, Express, React, Node.js) stack. It features user authentication, product management, and a dynamic shopping cart system.

## ✨ Key Features
*   User Authentication 🔐: Secure login and registration using JWT.
*   Product Management 📦: Dynamic product listings fetched from MongoDB Atlas.
*   Shopping Cart 🛒: Fully functional cart for adding and managing items.
*   Database Seeding ⚡: Built-in route to quickly populate the database with sample products.
*   Responsive Design 📱: Modern UI built with Tailwind CSS.

## 🛠️ Tech Stack
*   Frontend: React.js (via CDN for lightweight setup)
*   Backend: Node.js & Express.js
*   Database: MongoDB Atlas (Cloud)
*   Styling: Tailwind CSS

## 📈 Quick Setup

1. Clone the repository 📁:
   git clone [https://github.com/SonamSingh510/mern-ecommerce.git](https://github.com/SonamSingh510/mern-ecommerce.git)

2. Install Dependencies 🛠️:
   cd backend
   npm install express mongoose jsonwebtoken bcryptjs cors dotenv

3. Configure Environment 🔑:
   Create a .env file in the backend folder and add:
   MONGO_URI=your_mongodb_atlas_uri
   JWT_SECRET=your_secret_key

4. Run the Server ▶️:
   node server.js

5. Seed Data 🚀:
   Open http://localhost:5000/api/seed in your browser to add sample products.

6. Launch Frontend 🌐:
   Open index.html in any modern web browser.

## 📝 License
Distributed under the MIT License. Created by SonamSingh510 👨‍💻.
