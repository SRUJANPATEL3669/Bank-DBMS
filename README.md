# 💳 DB-Bank-System

A full-stack banking database management system built with **Next.js** and a robust backend, designed to streamline banking operations such as customer account management, loan tracking, transaction processing, employee and branch operations, and credit card processing.

## 🚀 Project Overview

This system is developed as part of the **CS257: Database and Information System** course. It addresses critical problems banks face such as handling vast, sensitive data and ensuring smooth, secure, and scalable operations for both customers and employees.

## 👨‍💻 Tech Stack

- **Frontend**: [Next.js](https://nextjs.org) (React)
- **Database**: Relational DB (MySQL/PostgreSQL - assumed)
- **ORM / Query**: SQL-based queries (explicit transactions handled with ACID compliance)
- **Authentication**: Email, Phone with bcrypt password hashing

---

## ⚙️ Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/DB-Bank-System.git
cd DB-Bank-System
```

### 2. Install dependencies

```bash
npm install
# or
yarn install
```

### 3. Run the development server

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🗃️ Key Features

### ✅ User Authentication
- Registration and Login using email, phone, and encrypted password
- Session handling and secure storage

### 💸 Transaction Management
- Fund transfers between accounts
- Transaction logging with full ACID compliance

### 🧾 Account Operations
- Account creation and management (Savings, Current)
- Fetching transaction history
- Balance and interest tracking

### 🧑‍💼 Employee & Branch Management
- Branch and employee records with structured ER-based schema

### 🏦 Loan & Credit Card Application
- Loan application with credit, income, and eligibility checks
- Credit card eligibility, limits, and status updates

---

## 🔄 Database ER Model

The system is based on a well-structured ER Model involving:

- `Customer`, `Account`, `Transaction`, `Loan`, `CreditCard`
- `Employee`, `Branch`, `University`, `Scholarship`

📊 View the full ER diagram:  
[🔗 View ER Diagram on draw.io](https://drive.google.com/file/d/1O8uSsGVstxxonvrOmFb1cKKvSy-v1oOU/view?usp=drive_link)

---

## 🔐 ACID-Compliant Transactions

Each transaction type in the system strictly maintains the four ACID properties:

| Transaction Type             | Atomic | Consistent | Isolated | Durable |
|-----------------------------|--------|------------|----------|---------|
| User Registration           | ✅     | ✅         | ✅       | ✅      |
| Fund Transfer               | ✅     | ✅         | ✅       | ✅      |
| Login                       | ✅     | ✅         | ✅       | ✅      |
| Loan Application            | ✅     | ✅         | ✅       | ✅      |
| Credit Card Application     | ✅     | ✅         | ✅       | ✅      |
| Retrieve Transaction History| ✅     | ✅         | ✅       | ✅      |

---

## 📁 Project Structure

```
DB-Bank-System/
├── app/
│   ├── page.tsx              # Home page
│   ├── api/                  # API routes
├── components/               # Reusable UI components
├── context/                  # Auth and App context
├── contracts/                # Smart contract (if used)
├── pages/                    # Routes
├── public/                   # Assets
├── styles/                   # Global styles
└── README.md
```

---

## 📦 Deployment

Deploy your application instantly with [Vercel](https://vercel.com/new?utm_source=create-next-app&utm_medium=default-template&utm_campaign=create-next-app).

📚 [Next.js Deployment Documentation](https://nextjs.org/docs/app/building-your-application/deploying)

---

## 📚 Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Interactive Next.js Tutorial](https://nextjs.org/learn)
- [Database Transaction Tutorial (ACID)](https://en.wikipedia.org/wiki/ACID)

---

## 👥 Contributors

- Aayush Yadav – 230001001  
- Divyam Maru – 230001025  
- **Srujan Patel** – 230001063  
- Nandini Kumari – 230001056  

---

## 📄 License

This project is for educational purposes. You can reuse or modify it with credit.
