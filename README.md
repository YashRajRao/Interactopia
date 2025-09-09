# 📱 Interactopia

A full-stack **Social Media Web Application** built with the MERN stack (MongoDB, Express.js, React.js, Node.js).  
This app provides core social networking features like posting, liking, commenting, following users, and authentication.



## 🚀 Features

✅ User Authentication (Signup/Login with JWT)  
✅ Create, Read, Update, Delete Posts  
✅ Like / Unlike Posts  
✅ Comment on Posts  
✅ Follow / Unfollow Users  
✅ User Profile Page  
✅ News Feed (Posts from followed users)  
✅ Secure Password Hashing with bcrypt  
---

## 🛠️ Tech Stack
### Backend:
- Node.js
- Express.js
- MongoDB (Mongoose ODM)

### Other:
- JWT (Authentication & Authorization)
- bcrypt (Password Encryption)
- Multer / Cloudinary (for image uploads if enabled)

 ## ⚡ Installation & Setup

### 1️⃣ Clone the repo
bash
git clone https://github.com/your-username/social-media-app.git
cd social-media-app

2️⃣ Backend Setup
bash
Copy code
cd backend
npm install
Create a .env file in backend/ with:

ini
Copy code
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
Run backend:

bash
Copy code
npm start
