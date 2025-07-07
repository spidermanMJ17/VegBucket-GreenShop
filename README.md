# 🥦 VegBucket – GreenShop 🌱  
**An Online Eco-Friendly Grocery Store | Built with MERN Stack**

![VegBucket Screenshot](https://drive.google.com/uc?export=view&id=1OawERr523nAkftPGAabIUUX8ofO0755y)

🌐 **Live Demo**: [VegBucket-GreenShop](https://veg-bucket-green-shop-bgpr.vercel.app/)

---

## 🧭 What is VegBucket?

**VegBucket** is an online green grocery store where users can:

- Browse fresh vegetables 🥬
- Add items to cart 🛒
- Login/Signup securely 🔐
- Place orders and view summaries 💳

---

## 🌟 Website Features

| ✅ Feature                    | 💻 Description                                                                 |
|-----------------------------|------------------------------------------------------------------------------|
| 👥 **Authentication**        | Register/Login securely with JWT-based auth                                  |
| 🛍️ **Product Browsing**      | See all vegetables with images, prices, and descriptions                     |
| ➕ **Add to Cart**           | Add/remove items with real-time cart update                                  |
| 🧾 **Cart Summary**          | Full order summary with item count and total price                           |
| 📲 **Mobile Responsive**     | Fully optimized for both desktop and mobile devices                          |
| 🔄 **Redux State Management**| Cart and user state managed efficiently across the app                       |

---

## 🔴 Live Demo Screenshots

| 🏠 Homepage | 🛒 Cart Page | 🔐 Login Page |
|------------|-------------|---------------|
| ![Home](https://via.placeholder.com/300x160?text=Homepage) | ![Cart](https://via.placeholder.com/300x160?text=Cart+Page) | ![Login](https://via.placeholder.com/300x160?text=Login+Page) |

> _You can replace these with real screenshots or GIFs of your deployed site._

---

## 🧱 Application Architecture

```mermaid
graph TD
A[React Frontend (Client)] -->|API Requests| B[Express Server (Backend)]
B --> C[MongoDB Database]
B --> D[JWT Auth & Middleware]
C --> B
