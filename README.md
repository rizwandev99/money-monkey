# 💸 Money Monkey – Personal Finance Manager

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]()
[![Tech Stack](https://img.shields.io/badge/Tech-Turbo%2C%20TypeScript%2C%20Postgres-blue)]()

A modern, monorepo-based personal finance management app. Track expenses, manage budgets, and visualize your financial health with a clean UI and robust backend.

---

## 🚀 Features

- 💰 Expense tracking
- 📊 Budget management
- 🏦 Multi-account support
- 📈 Analytics dashboard
- 🔒 Secure authentication
- 🌙 Dark mode
- 📱 Responsive design

---

## 🛠️ Tech Stack

- **Monorepo:** Turbo, TypeScript, Workspaces
- **Database:** PostgreSQL
- **Frontend & Backend:** Modular apps in `apps/` and shared code in `packages/`

---

## 🛠️ Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/rizwandev99/money-monkey.git
   cd money-monkey
   ```
2. **Install dependencies**
   ```bash
   npm install
   ```
3. **Set up environment variables**
   - Copy all `.env.example` files to `.env` and fill in your secrets.
4. **Run Postgres**
   - Locally or on the cloud (e.g., neon.tech)
   - Example (Docker):
     ```bash
     docker run -e POSTGRES_PASSWORD=mysecretpassword -d -p 5432:5432 postgres
     ```
5. **Migrate & seed database**
   ```bash
   cd packages/db
   npx prisma migrate dev
   npx prisma db seed
   ```
6. **Run the app**
   - Example: `cd apps/user-app && npm run dev`

---

## 🤔 Why Money Monkey?

- Turbo monorepo for scalable development
- Modern TypeScript everywhere
- Real-world finance features
- Clean, professional codebase

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.

---

## 📬 Contact

- [Email](mailto:rizwandev99@gmail.com)

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
