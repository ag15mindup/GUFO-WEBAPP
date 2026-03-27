# GUFO Web App

Full stack web application for a digital wallet and cashback ecosystem.

GUFO allows users to collect cashback, manage a digital balance and interact with partner businesses through a modern web platform.

---

## 🚀 Features

- User authentication (Supabase)
- Digital wallet (GUFO balance)
- Cashback system on transactions
- Dashboard with analytics and stats
- Transaction tracking
- Partner payment simulation
- Customer code system

---

## 🛠 Tech Stack

- Frontend: Next.js
- Backend: Node.js (Express)
- Database: Supabase
- Auth: Supabase Auth
- Deployment: Vercel (frontend) + Render (backend)

---

## 🌐 Live Demo

👉 https://gufo-frontend-edng.vercel.app/

---

## 📦 Project Structure---

## ⚙️ Main Functionalities

### Wallet System
- Users have a GUFO balance
- Cashback is automatically added after transactions

### Cashback Logic
- Users receive a percentage of cashback on payments
- Cashback is stored as GUFO currency

### Dashboard
- Total spent
- GUFO earned
- User level and stats
- Monthly expenses overview

### Partner System
- Simulated payments from merchants
- Customer identification via code (GUFO-XXXXXX)

---

## 🔐 API Overview

Main endpoints:

- `GET /wallet/:userId`
- `GET /transactions/:userId`
- `GET /dashboard/:userId`
- `POST /simulate-payment`
- `POST /transaction` (partner secured)

---

## 🎯 Project Goal

GUFO aims to create a new ecosystem where:

- Users earn and reuse cashback in a smart way
- Merchants gain insights and customer retention tools
- A digital wallet becomes a marketing and loyalty platform

---

## 📌 Status

MVP completed and fully working.

---

## 🤝 Contributing

Contributions are welcome.

---

## 👨‍💻 Author

Andrea Giardina
