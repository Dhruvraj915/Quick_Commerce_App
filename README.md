# ⚡ Quick Commerce App

The **Quick Commerce App** is a native Android application developed in **Java** using **XML layouts** and **SQLite** for local data storage. This project simulates a modern quick commerce platform — enabling users to explore products, manage their cart, and place orders — all within a smooth and intuitive user interface. It was built during my internship at **BrainyBeam Technologies** as a learning and hands-on experience in building real-world Android applications.

---

## 📱 Project Overview

The app is inspired by fast-paced e-commerce platforms that deliver convenience and efficiency. While real-world quick commerce platforms like Blinkit or Zepto are backed by powerful cloud services, this app demonstrates core e-commerce features locally — using **SQLite** for data persistence and custom logic for cart/order management.

This project serves as a base template or learning project for developers who want to understand how to build a structured e-commerce app in Android Studio without relying on external APIs.

---

## ✨ Key Features

### 👤 User Authentication
- User sign-up and login screens using local SQLite storage.
- Input validations for better UX.
- Stores credentials securely for local access.

### 🛍️ Product Catalog
- Product listing screen displaying products from a local database.
- Products organized by categories (e.g., groceries, electronics, etc.).
- Each product includes an image, title, description, and price.

### 🛒 Cart Management
- Users can add products to the cart.
- Cart summary with quantity management.
- Total price calculation.
- Remove items or update quantities in real-time.

### 📦 Order Placement
- Place an order after cart review.
- Order confirmation screen with summary.
- Order history stored locally for viewing previous orders (optional feature).

### 🧾 Database Integration
- Local SQLite database used to store:
  - User data
  - Product data
  - Cart items
  - Orders
- Custom `DBHelper` and `DAO` classes to manage CRUD operations efficiently.

### 🎨 Modern UI with XML
- Clean and responsive UI design using Android’s XML layout system.
- Custom themes, drawables, and icons for enhanced UI/UX.
- Supports various screen sizes.

---

## 🧱 Tech Stack

| Layer         | Technology         |
|---------------|--------------------|
| Language       | Java               |
| UI Design      | XML                |
| Local Database | SQLite             |
| IDE            | Android Studio     |
| Architecture   | MVC / Activity-Based |


