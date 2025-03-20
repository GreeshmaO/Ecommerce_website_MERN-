# 🛒 MERN Stack E-Commerce Website  

## 🚀 Project Overview  
This is a **full-featured E-Commerce website** built using the **MERN stack** (MongoDB, Express, React, Node.js). The website allows **users to browse products, view details, and place orders**, while the **admin panel** enables product management.  

## 📌 Features  
### 🔹 User Features  
✅ **View Products** – Browse all products on the home page  
✅ **View Product Details** – Click **View Details** to see product details  
✅ **Buy Now** – Add a product to the **Orders page**  
✅ **Orders List** – View purchased products  

### 🔹 Admin Features  
✅ **Admin Dashboard** – Manage products dynamically  
✅ **Add New Products** – Admin can add new products with images  
✅ **Delete Products** – Remove products from the store  
✅ **LocalStorage Management** – No backend required  



## 🏗️ Project Structure  

📦 ecompro2
┣ 📂 backend
┃ ┣ 📂 config           # Database & server configurations
┃ ┣ 📂 controllers      # Business logic for handling requests
┃ ┣ 📂 models          # Mongoose schemas
┃ ┣ 📂 routes          # API routes for users, products, orders
┃ ┣ 📜 server.js       # Main backend entry file
┃
┣ 📂 frontend
┃ ┣ 📂 public          # Public assets (favicons, index.html)
┃ ┣ 📂 src             # Frontend source files
┃ ┃ ┣ 📂 assets       # Images & static files
┃ ┃ ┣ 📂 components   # Reusable UI components (Navbar, Footer, ProductCard)
┃ ┃ ┣ 📂 pages        # Main pages (Home, Orders, Blogs, Contact, Admin)
┃ ┃ ┣ 📂 redux        # Redux store, slices, actions
┃ ┃ ┣ 📂 styles       # CSS stylesheets
┃ ┃ ┣ 📜 App.js       # Main React component
┃ ┃ ┣ 📜 index.js     # React entry point
┃
┣ 📜 package.json     # Dependencies & scripts
┣ 📜 README.md        # Project documentation

## ⚙️ Tech Stack  

### **Frontend (React)**  
- React.js  
- React Router DOM  
- Redux (State Management)  
- CSS (Responsive & Modern UI)  

### **Backend (Node.js & Express)**  
- Express.js  
- MongoDB (For backend projects)  
- Mongoose (MongoDB ORM)  

### **Other Tools**  
- LocalStorage (For storing orders & products)  
- Git & GitHub (Version Control)  



## 📥 Installation & Setup  

### 🔹 **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/GreeshmaO /Ecommerce_website_MERN-.git
cd ecompro2
🔹 2️⃣ Install Dependencies
🖥️ Backend Setup

cd backend
npm install
🌐 Frontend Setup

cd frontend
npm install
🔹 3️⃣ Run the Project
🖥️ Start Backend

cd backend
npm start
🌐 Start Frontend

cd frontend
npm start
💡 Now, open http://localhost:3000 in your browser.


Home Page	Product Details	Orders
🚀 Features Implementation
🏡 Home Page (Home.js)
✔ Loads all products from localStorage
✔ Shows "View Details" and "Buy Now" buttons

🛍️ Product Details (ProductDetails.js)
✔ Shows image, name, price, description
✔ "Buy Now" button adds product to orders

🛒 Orders Page (Orders.js)
✔ Lists all purchased products
✔ Data stored in localStorage

🔧 Admin Dashboard (AdminDashboard.js)
✔ Add Products – Admin can add product name, price & image
✔ Delete Products – Remove products dynamically
✔ Stored in LocalStorage

📝 Future Enhancements
🔹 User Authentication – Add Login/Signup
🔹 Payment Integration – Stripe/PayPal Checkout
🔹 Product Ratings & Reviews
🔹 Backend Database for Order Management






