# 🏦 Banking360 — Secure Banking Application

## Overview

Banking360 is a secure, full-stack banking application featuring a robust API layer for user authentication, transaction processing, and account management. Built with a focus on data integrity and financial security, the system implements industry-standard authentication mechanisms and relational database design with strict transaction constraints.

## Tech Stack

- **Frontend:** JavaScript, HTML5, CSS3
- **Backend:** Python / Node.js
- **Database:** SQL (Relational Database)
- **Authentication:** Secure API-based auth (JWT / session tokens)
- **Security:** Input validation, integrity constraints, secure headers
- **Tools:** VS Code, Git

## Features

- 🔐 **Secure Authentication** — API-based user login and registration with encrypted credentials
- 💸 **Transaction Processing** — Deposit, withdrawal, and transfer operations with integrity constraints
- 🗄️ **Account Management** — Create, update, and manage user banking accounts
- 📊 **Financial Ledger** — Relational database schema maintaining 100% financial accuracy
- 🛡️ **Security Layer** — Input sanitization, error handling, and access control enforcement
- 📋 **Transaction History** — Full audit trail of all financial operations per user

## How to Run

```bash
# Clone the repository
git clone https://github.com/Phoenixking-04/FDB-Project.git
cd FDB-Project/bankingSystem

# Install dependencies
pip install -r requirements.txt
# or for Node.js: npm install

# Set up the database
python manage.py migrate
# or: run the SQL schema scripts

# Configure environment variables
cp .env.example .env
# Set DATABASE_URL, SECRET_KEY, etc.

# Start the server
python manage.py runserver
# or: node server.js
```

## Results / Outcomes

- ✅ Implemented **secure API authentication** with encrypted credential storage
- ✅ Designed a **normalized relational database** schema ensuring financial ledger accuracy
- ✅ Enforced **transaction integrity constraints** to prevent data corruption
- ✅ Built a full **account lifecycle management** system (create, update, close)
- ✅ Delivered end-to-end **security layer** with input validation and access control

---

> 🔗 **Developer:** [Kalyankumar Sandireddy](https://kalyankumar-sandireddy.online) | [LinkedIn](https://www.linkedin.com/in/kalyankumar-sandireddy-400681176)
