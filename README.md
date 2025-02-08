# 🚀 Event Management System

A full-stack **Event Management System** that allows users to create, manage, and register for events. Built using **MERN Stack** (MongoDB, Express.js, React.js, Node.js).

---

## 💁️ Project Structure
```
event-management-system/
│── backend/         # Node.js + Express + MongoDB
│── frontend/        # React.js + Tailwind CSS
│── README.md        # Project Documentation
│── package.json     # Dependencies
│── .gitignore       # Ignored files
```

---

## 🛠 **Tech Stack**
### **Frontend:**
- React.js
- Tailwind CSS
- Axios (for API requests)
- React Router

### **Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose for ODM)
- JWT Authentication
- Cloudinary (for image uploads)

---

## 🔥 **Getting Started**
### 🖥 **1. Clone the Repository**
```sh
git clone https://github.com/ANJALINITA/Swissmote_Assignment_Anjali.git
cd event-management-system
```

---

## ⚙️ **Backend Setup**
### **2. Navigate to Backend Folder**
```sh
cd backend
```

### **3. Install Dependencies**
```sh
npm install
```

### **4. Set Up Environment Variables**
Create a `.env` file in the `backend` folder and add:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### **5. Run Backend Server**
```sh
npm start
```
Server will run on: `http://localhost:5000`

---

## 🎨 **Frontend Setup**
### **6. Navigate to Frontend Folder**
```sh
cd ../frontend
```

### **7. Install Dependencies**
```sh
npm install
```

### **8. Start React Development Server**
```sh
npm start
```
Frontend will run on: `http://localhost:3000`

---

## 🔗 **API Endpoints**
| Method | Endpoint | Description |
|--------|---------|------------|
| POST   | /api/auth/register | Register a new user |
| POST   | /api/auth/login | Login user |
| GET    | /api/events | Get all events |
| POST   | /api/events | Create an event |
| PUT    | /api/events/:id | Update an event |
| DELETE | /api/events/:id | Delete an event |

---

## ✅ **Features**
✔️ User Authentication (Login/Register)  
✔️ Create & Manage Events  
✔️ Event Registration  
✔️ Secure API using JWT  
✔️ Cloudinary for Image Uploads  
✔️ Responsive UI  

---

## 🛠 **Troubleshooting**
- If **MongoDB connection fails**, check your `MONGO_URI` in `.env`.  
- If `EADDRINUSE` error occurs, another process is using the port. Try:  
  ```sh
  kill -9 $(lsof -t -i:5000)
  ```

---

## 🐝 **License**
This project is licensed under the **MIT License**.

---

## 📨 **Contact**
👤 **Anjali Singh**  
📧 Email: anjalisingh221220030@gmail.com  
🔗 GitHub: [ANJALINITA](https://github.com/ANJALINITA)  

---

This **README.md** provides a complete guide for setting up and running your project. Let me know if you need any modifications! 🚀😊  

