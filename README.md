# ♻️ EcoFinds – Empowering Sustainable Second-Hand Marketplaces

**EcoFinds** is a second-hand marketplace platform built for a circular economy. We help people buy and sell pre-owned items easily, promoting sustainability through features like auctions, chat-based deals, and community trust systems.

---

## 🌟 Hackathon Summary

- **Goal**: Build a cross-platform MVP (mobile + desktop web)
- **Key Features**:
  - OTP/Email authentication
  - Product listings and live auctions
  - Buyer-seller chat
  - Personalized feeds & search filters
  - Admin dashboard for complaints
  - Modern and intuitive UI

- **Tech Stack**:
  - **Frontend**: React.js
  - **Backend**: Node.js + Express.js
  - **Database**: MongoDB
  - **AI-Assistance**: Used **Blackbox** to accelerate development

---

## ✅ Features Implemented

### 🔐 Authentication & User Profiles
- OTP and email verification
- Secure login/signup with JWT
- User dashboard with editable profile

### 📦 Listings & Auctions
- Post, update, and delete products with images
- Create time-based auctions with min-bid rules
- Real-time bidding interface

### 🔎 Discovery & Recommendations
- Search bar with filters (price, location, category, condition)
- "You Might Like" feed based on user activity
- Save search alerts for price drops

### 💬 Chat & Transactions
- In-app buyer-seller messaging
- Add items to cart
- View purchase history and rate sellers

### 🛡️ Trust & Safety
- Buyer/seller ratings
- Complaint system for disputes
- Admin dashboard for moderation

### 🌐 Multi-language Support
- English (default)
- Hindi and Gujarati for wider accessibility

---

## 🧠 Why It Matters

> EcoFinds is not just a marketplace — it’s a platform that enables sustainable commerce with trust, transparency, and tech.

- **Community-Focused**: Ratings & moderation build user trust
- **Eco-Friendly**: Encourages reuse and responsible buying
- **AI-Powered Dev**: Used Blackbox to rapidly generate clean, tested code
- **Scalable**: Modular design for future enhancements

---

## 🗂️ Project Structure

EcoFinds/

├── backend/ # Node.js backend

│ ├── controllers/ # Logic for each API route

│ ├── models/ # Mongoose schemas

│ ├── routes/ # Express API endpoints

│ ├── middleware/ # Auth, error handlers, OTP

│ └── utils/ # Helper functions and validators

│
├── frontend/ # React frontend

│ ├── components/ # UI components

│ ├── pages/ # Main page views

│ ├── services/ # API integration

│ └── styles/ # CSS and theme files
