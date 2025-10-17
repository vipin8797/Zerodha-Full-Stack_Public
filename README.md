# 💹 Stock_Trading_App
A full-stack MERN web application simulating stock trading, inspired by Zerodha, with features like dashboard, holdings, buy/sell orders, and charts.


## 📑 Table of Contents
1. [Features](#features)
2. [Tech Stack](#tech-stack)
3. [Folder Structure](#folder-structure)
4. [Installation & Setup](#installation--setup)
5. [Usage](#usage)
6. [API Endpoints](#api-endpoints)
7. [Screenshots](#screenshots)
8. [Future Enhancements](#future-enhancements)
9. [Author](#author)




## 🚀 Features
- Secure login/signup with JWT
- Dashboard showing portfolio and market summary
- Buy/Sell stocks with mock trading
- Holdings, Orders, Positions, Funds sections
- Real-time charts using Chart.js
- Additional pages: About, Products, Pricing, Support


## 🧠 Tech Stack
| Layer       | Technology |
|------------|------------|
| Frontend    | HTML, CSS, JS, Chart.js |
| Backend     | Node.js, Express.js |
| Database    | MongoDB |
| Auth        | JWT |
| API         | REST APIs for orders, holdings, positions |



## 🗂️ Folder Structure
Stock_Trading_App/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   └── server.js
├── frontend/
│   ├── index.html
│   ├── css/
│   ├── js/
│   ├── charts/
│   └── pages/
├── .gitignore
├── package.json
├── README.md
└── .env.example



## ⚙️ Installation & Setup
1. Clone the repo:
```bash
git clone https://github.com/vipinyadav/Stock_Trading_App.git
cd Stock_Trading_App


npm install



PORT=3000
MONGODB_URL=your_mongo_connection_string
JWT_SECRET=your_secret


npm start



#### **Usage**
```markdown
## 🖥️ Usage
- Teacher/Admin: log in → add stock data (if any admin feature)
- User: log in → view dashboard, buy/sell stocks, check holdings
- Track orders and positions in real time




## 🔌 API Endpoints
| Method | Endpoint         | Description                  |
|--------|-----------------|-----------------------------|
| POST   | /api/auth/login | Login existing user         |
| POST   | /api/auth/signup| Register new user           |
| GET    | /api/holdings   | Get user holdings           |
| POST   | /api/order      | Place buy/sell order        |
| GET    | /api/positions  | Get open positions          |



## 📸 Screenshots
| Dashboard | Holdings | Orders |
|-----------|---------|--------|
| ![Dashboard](screenshots/dashboard.png) | ![Holdings](screenshots/holdings.png) | ![Orders](screenshots/orders.png) |




## 🌟 Future Enhancements
- Real-time stock prices using WebSocket
- AI-powered trade suggestions
- Cloud deployment on Render or Vercel
- Advanced analytics dashboard



## 👨‍💻 Author
Vipin Yadav  
MERN Stack Developer  
[LinkedIn](https://linkedin.com/in/vipinyadav) | [GitHub](https://github.com/vipinyadav)
