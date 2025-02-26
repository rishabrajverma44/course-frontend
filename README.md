# MERN Stack Authentication & Payment App

## 🚀 Project Overview

This is a **full-stack authentication and payment application** built using the **MERN stack**. It features **JWT-based user authentication and authorization** with email verification services and **Razorpay payment gateway integration**.

## 🛠 Tech Stack

- **MongoDB** - Database
- **Express.js** - Backend framework
- **React.js** - Frontend library
- **Node.js** - Server environment
- **JWT** - Authentication & Authorization
- **Razorpay** - Payment Gateway

## 🔑 Features

✅ User registration with email verification  
✅ Secure login/logout with JWT authentication  
✅ Role-based access control  
✅ Password hashing for security  
✅ Razorpay payment gateway integration  
✅ Responsive UI with React  

## 🔧 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rishabrajverma44/course-frontend.git
   cd course-frontend
   ```

2. **Install dependencies:**
   ```bash
   # Install backend dependencies
   cd backend
   yarn install
   
   # Install frontend dependencies
   cd ../frontend
   yarn install
   ```

3. **Set up environment variables:**  
   Create a `.env` file in the `backend` folder and configure the following:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   EMAIL_SERVICE=your_email_service_provider
   EMAIL_USER=your_email_username
   EMAIL_PASS=your_email_password
   RAZORPAY_KEY_ID=your_razorpay_key_id
   RAZORPAY_KEY_SECRET=your_razorpay_key_secret
   ```

4. **Run the application:**
   ```bash
   # Start backend server
   cd backend
   yarn start
   
   # Start frontend server
   cd ../frontend
   yarn start
   ```
   The frontend will run on `http://localhost:3000` and the backend on `http://localhost:5000`.

## 🔗 Live Demo
[Course Web App - Live](https://course-frontend-pi.vercel.app/signin)

## 📌 Usage
- **Register/Login** with email verification.
- **Authenticate** users using JWT.
- **Authorize** access based on roles.
- **Make Payments** using Razorpay.

## 🎯 Future Plans
🔹 Enhance security with multi-factor authentication  
🔹 Add social authentication (Google, Facebook)  
🔹 Implement subscription-based payment models  
🔹 Improve UI/UX for a better user experience  

## 🎯 Deployment
This project can be deployed on:
- **Frontend:** Vercel/Netlify
- **Backend:** Heroku/Render
- **Database:** MongoDB Atlas

## 🤝 Contributing
Feel free to fork the repo, open issues, and submit pull requests!

## 📜 License
This project is licensed under the MIT License.

## 📬 Contact
For support or inquiries, contact [rishabrajverma44](https://github.com/rishabrajverma44).

