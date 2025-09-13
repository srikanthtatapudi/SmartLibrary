# 📚 Smart Library Management System  

A full-stack web application to streamline library operations such as **seat reservation, rack management, and seminar scheduling**.  
Built with **Node.js, Express, MongoDB**, and a simple **HTML/CSS/JS frontend**.  

---

## 🚀 Features  

- ✅ **Seat Reservation** – Book, cancel, and check seat availability in reading rooms & GD rooms  
- ✅ **Rack Management** – Organize, locate, and manage books in racks  
- ✅ **Seminar Scheduling** – Reserve seminar halls with proper time-slot management  
- ✅ **Time-Based Rules** – Seat availability only between **9:30 AM – 4:20 PM**, hidden after **4 PM**  
- ✅ **Admin Panel** – Manage seats, racks, and seminars efficiently  

---

## 🛠️ Tech Stack  

<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,html,css,javascript,netlify,heroku" />
</p>

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Node.js + Express.js  
- **Database**: MongoDB (Mongoose ORM)  
- **Deployment**: Netlify (Frontend), Render/Heroku (Backend), MongoDB Atlas (Database)  

---

## 🏗️ Project Setup  

### 1. Clone the Repository  
```bash
git clone https://github.com/srikanthtatapudi/SmartLibrary.git
cd SmartLibrary
```
### 2.Backend Setup
```bash
cd backend
npm install
```
###Install dependencies:
```
npm install express mongoose bcryptjs jsonwebtoken dotenv cors

```
###Create a .env file in the backend/ folder:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

###Seed initial data (optional):
```
node scripts/seedData.js
```

###Run the server:
```
node server.js
```

👉 Backend will run on: http://localhost:5000

3. Frontend Setup

No build tools required (static HTML/CSS/JS)

Place assets like aditya.png, astro.png, and human.png inside the frontend/ folder

Open frontend/index.html directly in a browser

(Optional) Deploy frontend via Netlify

📂 Folder Structure
```
SmartLibrary/
│── backend/                
│   ├── config/             # DB config, env setup
│   ├── controllers/        # Business logic
│   ├── middleware/         # Auth, validation
│   ├── models/             # MongoDB schemas
│   ├── routes/             # Express routes
│   ├── scripts/            # Data seeding
│   ├── utils/              # Helper functions
│   ├── server.js           # Backend entry point
│   └── package.json
│
│── frontend/               # Static frontend files
│   ├── index.html
│   ├── styles.css
│   ├── script.js
│   ├── aditya.png
│   ├── astro.png
│   └── human.png
│
│── .gitignore
│── README.md
│── SECURITY.md
```
