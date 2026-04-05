# 🛒 Grocery Inventory Management System

A modern full-stack web application to manage products, suppliers, and stock efficiently with a clean and colorful UI.

---

## ✨ Features

* Add new products with supplier selection
* View all products in a dynamic table
* Edit product details inline
* Delete products instantly
* Stock-level color indicators (Low / Medium / High)
* Supplier management integration
* Responsive and modern UI with gradients

---

## 🖼️ UI Preview

<img width="1363" height="911" alt="image" src="https://github.com/user-attachments/assets/b4af5aae-d908-48b6-a72f-35bf64f22ab6" />


---

## 🛠️ Tech Stack

### Frontend

* React.js
* Axios
* Tailwind CSS

### Backend

* Node.js
* Express.js

### Database

* MySQL

---

## ⚙️ Project Structure

```
inventory-management-system/

├── backend/
│   ├── db.js
│   ├── server.js
│   ├── package.json

├── frontend/
│   ├── src/
│   ├── package.json

└── README.md
```

---

## 🚀 How to Run Locally

### 1. Clone the repository

```
git clone https://github.com/keerthanavoffl/inventory-management-system.git
cd inventory-management-system
```

---

### 2. Setup Backend

```
cd backend
npm install
npm start
```

Server runs on:

```
http://localhost:5000
```

---

### 3. Setup Frontend

```
cd frontend
npm install
npm start
```

App runs on:

```
http://localhost:3000
```

---

## 🔌 API Endpoints

| Method | Endpoint      | Description       |
| ------ | ------------- | ----------------- |
| GET    | /products     | Get all products  |
| GET    | /suppliers    | Get all suppliers |
| POST   | /products     | Add product       |
| PUT    | /products/:id | Update product    |
| DELETE | /products/:id | Delete product    |

---

## 🎨 UI Highlights

* Gradient background design
* Glassmorphism cards (blur + transparency)
* Color-coded stock levels:

  * Low (<5)
  * Medium (<15)
  * High
* Smooth hover animations

---

## 🔒 Environment Variables

Create a `.env` file in backend:

```
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=inventory
```

---

## 👩‍💻 Author

Keerthana

---

## ⭐ Future Improvements

* Authentication (Login/Register)
* Dashboard analytics
* Search & filter products
* Deploy to cloud (Render + Vercel)

---

## 💡 Notes

* Make sure MySQL is running
* Create required tables before running backend

---

## 🌐 Live Demo

Coming soon...
