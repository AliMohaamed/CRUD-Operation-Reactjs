# 🛍️ ReactJS CRUD Products App

This project is a **ReactJS CRUD application** for managing products, connected to a mock API using **json-server**.

You can **Add, Edit, View, and Delete products** through a simple user interface.

---

## 🚀 Features

✅ View all products  
✅ Add a new product  
✅ Edit existing products  
✅ Delete products  
✅ Connected to a mock REST API using json-server

---


---

## 🛠️ **Getting Started**

### 1️⃣ Clone the repository

```bash
git clone https://github.com/AliMohaamed/CRUD-Operation-Reactjs
cd CRUD-Operation-Reactjs

npm install
make folder server
cd server
npm init -y
npm install json-server --save-dev
Inside /server:
{
  "products": [
    { "id": 1, "name": "Product 1", "price": 100 },
    { "id": 2, "name": "Product 2", "price": 200 }
  ]
}

npx json-server --watch db.json --port 3001

npm start

