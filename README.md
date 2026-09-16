# 💰 Expense Tracker

A full-stack **Expense Tracker Web Application** developed as **Project 1** during the SyntechHub Web Development Internship.

The application allows users to securely manage their income and expenses, view their financial summary, analyze spending patterns, and manage their personal profile.

---

## 📌 Project Overview

The Expense Tracker is designed to help users keep track of their personal finances through a simple and responsive web interface.

Users can:

- Create an account
- Log in securely
- Manage their profile
- Upload a profile photo
- Add income records
- Add expense records
- Edit existing transactions
- Delete transactions
- View total income
- View total expenses
- View current balance
- View savings rate
- Analyze spending by category
- View expense trends
- Check recent transactions
- View budget/spending status

---

## ✨ Features

### 🔐 User Authentication

- User registration
- User login
- JWT-based authentication
- Password protection using bcrypt
- Protected API routes
- Automatic authentication handling

### 👤 Profile Management

- View user profile
- Edit profile information
- Update profile details
- Upload and update profile photo
- Display profile information throughout the application

### 💵 Income Management

- Add income records
- View recorded income
- Edit income records
- Delete income records
- Calculate total income
- Display income transaction history

### 💸 Expense Management

- Add expense records
- View recorded expenses
- Edit expense records
- Delete expense records
- Categorize expenses
- Calculate total expenses
- Display expense transaction history

### 📊 Dashboard

The dashboard provides a financial overview containing:

- Total Balance
- Total Income
- Total Expenses
- Savings Rate
- Expense Overview
- Spending by Category
- Recent Transactions
- Budget Status
- Financial Tips

### 📈 Expense Analysis

Users can view expense trends for:

- Last 7 days
- Last 30 days
- Last 3 months

The dashboard also groups expenses by category to provide a clear view of where money is being spent.

### 📱 Responsive Design

The application is designed to work across different screen sizes, including:

- Desktop
- Laptop
- Tablet
- Mobile devices

---

## 🛠️ Technologies Used

### Frontend

- React
- Vite
- JavaScript
- HTML
- CSS

### Backend

- Node.js
- Express.js
- REST API
- JSON Web Token (JWT)
- bcrypt

### Database

- MongoDB
- MongoDB Atlas

### Development Tools

- Visual Studio Code
- Git
- GitHub
- Postman
- MongoDB Atlas
- npm

---

## 🏗️ Application Architecture

```text
                    ┌──────────────────────┐
                    │       User           │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │   React Frontend     │
                    │       + Vite         │
                    └──────────┬───────────┘
                               │
                         HTTP / REST API
                               │
                               ▼
                    ┌──────────────────────┐
                    │   Express Backend    │
                    │      Node.js         │
                    └──────────┬───────────┘
                               │
                         JWT Authentication
                               │
                               ▼
                    ┌──────────────────────┐
                    │    MongoDB Atlas     │
                    │      Database        │
                    └──────────────────────┘