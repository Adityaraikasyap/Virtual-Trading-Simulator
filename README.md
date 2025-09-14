
---

# 📈 Mock Stocks - MERN Stack Trading Simulation

*Mock Stocks* is a simulated trading and investment platform built using the *MERN Stack: MongoDB, Express.js, React, and Node.js. It allows users to view fake stock data, simulate buying/selling, and view investment performance in real-time using **Socket.IO*.

> ⚠ This is a *mock platform* – stock prices and data are *not real* and are randomly generated for learning/demo purposes.

---

## 🚀 Tech Stack (MERN)

### 🔧 Back-End

* *MongoDB* – Database for storing user data, stocks, transactions
* *Express.js* – REST API framework
* *Node.js* – Server environment
* *Socket.IO* – Real-time stock price updates

### 🎨 Front-End

* *React* – Component-based UI
* *Redux* – State management
* *TailwindCSS* – Utility-first styling
* *Chart.js* – Visualizing stock trends

---

## 📁 Project Structure


/backend     # Node.js + Express + MongoDB
/frontend    # React + Redux UI


---

## 🛠 Running the Project Locally

### 1. Clone the Repo

bash
git clone https://github.com/Adityaraikasyap/Virtual-Trading-Simulator


### 2. Setup Back-End

bash
cd backend
npm install


Create a .env file in /backend:

env
MONGO_CONNECTION_STRING=your_mongo_uri
JWT_SECRET=your_jwt_secret
GUEST_ID=guest_user_id


Run the server:

bash
node index.js


### 3. Setup Front-End

bash
cd frontend
npm install


Create a .env file in /frontend:

env
REACT_APP_STOCKS_API=http://localhost:5000
REACT_APP_GUEST_EMAIL=your_base64_email
REACT_APP_GUEST_PASS=your_base64_password


Run the React app:

bash
npm start


---

---
