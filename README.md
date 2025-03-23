# User Authentication API

This is a simple user authentication API built with Node.js, Express, and MongoDB. It allows users to register and log in securely using bcrypt for password hashing and JWT for authentication.

---

## 📌 Features

✅ User Registration with Hashed Passwords  
✅ Secure Login with JWT Authentication  
✅ MongoDB Integration with Mongoose  
✅ Environment Variables Support via `.env`  
✅ CORS Support for Cross-Origin Requests  

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/auth-api.git
cd auth-api
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Setup Environment Variables
Create a `.env` file in the root directory and add the following:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

### 4️⃣ Start the Server
```bash
npm start
```
The server will run on `http://localhost:5000`

---

## 📌 API Endpoints

### 🔹 Register a New User
**Endpoint:** `POST /register`

**Request Body:**
```json
{
  "username": "john_doe",
  "password": "securepassword",
  "email": "johndoe@example.com",
  "phone": 1234567890,
  "address": "123 Main St",
  "city": "New York",
  "state": "NY",
  "country": "USA",
  "pincode": 10001
}
```

**Response:**
```json
{
  "message": "User registered successfully"
}
```


---

### 🔹 User Login
**Endpoint:** `POST /login`

**Request Body:**
```json
{
  "username": "john_doe",
  "password": "securepassword"
}
```

**Response:**
```json
{
  "token": "your_jwt_token"
}
```

---

## 🌍 Deployment to GitHub

1. Initialize a Git repository
```bash
git init
git add .
git commit -m "Initial commit"
```

2. Create a new repository on GitHub and push the code
```bash
git remote add origin https://github.com/your-username/auth-api.git
git branch -M main
git push -u origin main
```



## 📷 Project Overview
### 📌 Folder Structure
```
📁 auth-api/
│-- 📄 server.js
│-- 📄 .env
│-- 📄 package.json
│-- 📄 README.md
│-- 📁 node_modules/
```



## 🛠 Technologies Used
- **Node.js** - JavaScript runtime
- **Express.js** - Web framework
- **MongoDB** - Database
- **Mongoose** - ODM for MongoDB
- **bcrypt.js** - Password hashing
- **jsonwebtoken (JWT)** - Authentication
- **dotenv** - Environment variable management
- **CORS** - Cross-Origin Resource Sharing

---

## 🔗 Useful Links
- [MongoDB Setup Guide](https://www.mongodb.com/docs/)
- [Node.js Documentation](https://nodejs.org/en/docs/)
- [Express.js Documentation](https://expressjs.com/)

---

## 📝 License
This project is open-source and available under the MIT License.

---

📧 Need help? Feel free to reach out!

mail tejashwin2004teju@gmail.com
mobile 7795500636
insta @faceofteju
