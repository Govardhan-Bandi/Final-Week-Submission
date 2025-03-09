# 🏆 Auction App

A real-time online auction platform where users can place bids, manage auctions, and track bidding activity.

## 🚀 Features
✅ **Real-Time Bidding** (WebSockets)  
✅ **User Authentication** (JWT-based login/signup)  
✅ **Secure Password Hashing** (bcrypt)  
✅ **Auction Management** (Post, Edit, Delete Auctions)  
✅ **Responsive UI** (TailwindCSS/Material-UI)  
✅ **MongoDB Atlas for Cloud Database**  

## 🛠 Tech Stack
- **Frontend:** React.js, React Router, WebSockets (Socket.io)  
- **Backend:** Node.js, Express.js, MongoDB  
- **Database:** MongoDB Atlas  
- **Authentication:** JWT, bcrypt  
- **Deployment:** Vercel (Frontend), Render (Backend)  

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/auction-app.git
cd auction-app
```

### 2️⃣ Backend Setup  
```bash
cd backend
npm install
```  
Create a `.env` file in the `backend` folder and add:
```
MONGO_URI=mongodb+srv://your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_jwt_secret
```

Run the backend server:  
```bash
npm start
```

### 3️⃣ Frontend Setup  
```bash
cd frontend
npm install
npm start
```  

## 🚀 Deployment  
- **Frontend:** Deploy on [Vercel](https://vercel.com/)  
- **Backend:** Deploy on [Render](https://render.com/)  

## 📜 License  
This project is open-source and free to use.  
