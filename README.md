# ☕ Acorn App (MERN Stack)

This is a **full-stack cafe ordering system** built for Yale's Acorn Cafe with the **MERN stack (MongoDB, Express, React, Node.js)**.  
Customers can **browse the menu and add items to their cart**, while **owners can manage the menu** by adding new items.

---

## 📌 Features
### 🌍 **Public Users (Customers)**
- View the cafe menu **without logging in**.
- Add items to a **cart** and place orders.
- Checkout using **Stripe** (optional).

### 🔑 **Owner Dashboard**
- **Login as an Owner** (via `/owner` route).
- See the same menu **but with an extra "+" button** for adding new items.
- Click the "+" button to open a **modal** where new menu items can be added.
- Items update **instantly** on the menu after being added.

### 💾 **Database**
- **MongoDB stores only owner accounts, menu items, and orders.**
- Customers do not need to register or log in.

---

## 🛠️ Installation

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
