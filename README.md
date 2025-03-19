# Personal Finance & Budget Tracker

A **Personal Finance & Budget Tracker** that helps users manage income and expenses efficiently. Built with **HTML, CSS, JavaScript (Frontend)** and **Node.js, Express, MongoDB (Backend)**.

## 🚀 Features

### ✅ **Frontend (HTML, CSS, JavaScript, Chart.js)**
- User-friendly UI for adding transactions (income/expenses).
- Real-time balance updates.
- Transaction history.
- **Chart.js integration** for visualizing spending trends.
- Responsive design.

### ✅ **Backend (Node.js, Express, MongoDB)**
- REST API for managing transactions.
- **CRUD Operations** (Create, Read, Update, Delete transactions).
- Stores transactions securely in MongoDB.
- API built with Express.js.

---

## 📂 **Project Structure**

### Frontend (`finance-tracker-frontend/`)
```
finance-tracker-frontend/
│── index.html         # Main UI
│── style.css         # Styling
│── script.js         # Frontend logic (Fetch API, LocalStorage handling)
│── charts.js         # Handles Chart.js integration
│── assets/           # Icons, images
```

### Backend (`finance-tracker-backend/`)
```
finance-tracker-backend/
│── server.js         # Main Express server
│── package.json      # Project dependencies
│── config/           # Database connection config
│── models/           # Transaction model
│── routes/           # API routes for transactions
```

---

## ⚡ **Installation & Setup**

### **1️⃣ Clone the Repository**
```
git clone https://github.com/KoushikScripts/finance-tracker.git
cd finance-tracker
```

### **2️⃣ Install Frontend Dependencies**
```
cd finance-tracker-frontend
npm install
```

### **3️⃣ Install Backend Dependencies**
```
cd ../finance-tracker-backend
npm install
```

### **4️⃣ Set Up Environment Variables**
Create a `.env` file inside `finance-tracker-backend/` and add:
```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

### **5️⃣ Start Backend Server**
```
cd finance-tracker-backend
node server.js
```
✅ Server runs on `http://localhost:5000`

### **6️⃣ Open Frontend (`index.html`)**
Open `index.html` in your browser or use Live Server.

---

## 📡 **API Endpoints**
| Method | Endpoint          | Description                |
|--------|------------------|----------------------------|
| GET    | `/transactions`  | Fetch all transactions     |
| POST   | `/transactions`  | Add a new transaction      |
| DELETE | `/transactions/:id` | Delete a transaction by ID |

---

## 📊 **How It Works?**
1. **User enters a transaction** (Description & Amount).
2. **Transaction is saved in the backend (MongoDB).**
3. **Frontend fetches and updates balance & chart dynamically.**

---

## 🤝 **Contributing**
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make changes & commit (`git commit -m 'Added a new feature'`).
4. Push changes (`git push origin feature-branch`).
5. Create a Pull Request.

---

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## ✨ **Future Enhancements**
- **User Authentication** (Login & Signup system).
- **Export Data** (Download transactions as CSV/PDF).
- **Google Sheets Integration** (Alternative to DB storage).

🚀 Happy Coding!

