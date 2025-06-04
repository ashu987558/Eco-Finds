♻️ EcoFinds – Empowering Sustainable Second-Hand Marketplaces
EcoFinds is a second-hand marketplace platform designed to promote a sustainable, circular economy by making it easy for people to buy and sell pre-owned items. Our platform empowers users to make eco-conscious decisions by offering features like auctions, chat-based negotiations, personalized recommendations, and community-driven trust systems.

🌟 Hackathon Summary

Team Focus: Building a cross-platform (desktop & mobile web) MVP that handles:
User authentication with OTP/email verification
Product listings and auctions
Buyer-seller chat
Advanced filters and personalized feeds
Admin dashboard for complaints
A modern and intuitive user interface

Technology Stack:
Frontend: React.js
Backend: Node.js + Express.js
Database: MongoDB
AI-Powered Development: Leveraged Blackbox to rapidly generate production-quality code (CRUD logic, APIs, UI components, validation logic, etc.)

🧩 Features Implemented
1. Authentication & User Profiles
OTP and Email Verification
Login/Signup with secure JWT sessions
Editable User Dashboard
2. Listings & Auctions
Post, update, delete products with images
Set up auctions with min bids and durations
Live auction interface with countdown and bidding logic
3. Discovery & Recommendations
Search bar + advanced filters (price, condition, category, location)
Personalized "You Might Like" feed (based on browsing history)
Saved searches and price-drop alerts
4. Communication & Transactions
In-app chat between buyers and sellers
Cart system for reviewing multiple listings
View past purchases and leave ratings
5. Trust & Safety
Seller & buyer ratings
Dispute resolution system
Admin dashboard for managing complaints and flagged users
6. Multi-language Support
English (default)
Hindi & Gujarati support for accessibility

🏗️ Project Structure
bash
Copy
Edit
EcoFinds/
├── backend/           # Node.js Express API

│   ├── controllers/   # Business logic for each route

│   ├── models/        # Mongoose schemas for MongoDB

│   ├── routes/        # API endpoints

│   ├── middleware/    # Auth, error handlers, OTP

│   └── utils/         # Reusable validators and helpers

│
├── frontend/          # React frontend

│   ├── components/    # Reusable UI components

│   ├── pages/         # Route-specific views

│   ├── services/      # API integration logic

│   └── styles/        # CSS and theming


🧠 Implementation Plan
Why Odoo team should be interested:
Modular Design: Clear separation between frontend, backend, and services for scalability.

Rapid Prototyping via Blackbox: Our team has efficiently used Blackbox AI to code faster and cover more features within the hackathon timeframe.

Real-World Ready: Key e-commerce features like chat, ratings, auctions, cart, and moderation are implemented and extensible.

Community Trust Focus: Built-in user rating system and dispute resolution mechanisms ensure a safe user environment.

Localized for India: With Hindi and Gujarati UI support and mobile-first design.
