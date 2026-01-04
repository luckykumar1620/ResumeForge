# 📄 ResumeForge

A full-stack **ResumeForge web application** that enables users to create, customize, and manage professional resumes with ease.  
The project follows **industry-level architecture**, secure authentication, and clean UI/UX practices.

---

## 🚀 Key Features

- 🧑‍💼 User authentication (Signup & Login)
- 🔐 Secure JWT-based authorization
- 🎨 Multiple professional resume templates
- ✏️ Live resume preview & editing
- 🖼️ Profile image upload support
- 📥 Download resumes in PDF format
- 📱 Fully responsive (Mobile + Desktop)
- ⚡ Fast and scalable architecture

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS
- JavaScript (ES6+)

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Authentication & Media
- JWT (JSON Web Token)
- bcryptjs
- ImageKit (for image handling)

### Tools
- Git & GitHub
- dotenv
- Postman

---

## 🔐 Authentication System (JWT)

This project uses **JWT-based authentication** for secure user login and authorization.

### Authentication Flow
1. User signs up or logs in with email & password
2. Passwords are securely hashed using bcrypt
3. Server generates a JWT token
4. Token is sent to the client
5. Protected routes are accessed using the token

### Benefits
- Stateless & scalable authentication
- Secure API access
- Supports protected routes and future role-based access

---

## 🖼️ Image Handling (ImageKit)

**ImageKit** is integrated for efficient image management.

### Use Cases
- User profile photo
- Resume image uploads

### Benefits
- Automatic image optimization
- Fast CDN delivery
- Reduced backend load
- Secure upload mechanism

> ⚠️ ImageKit is used only for media storage and delivery, not for authentication.

---

## 📂 Project Structure

```text
resume-builder/
│── client/                 # Frontend application
│── server/                 # Backend application
│   │── .env.example        # Environment variable template
│   │── .gitignore
│   │── routes/
│   │── controllers/
│   │── models/
│── README.md

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/resume-builder.git
cd resume-builder
2️⃣ Install dependencies
Backend
cd server
npm install
Frontend
cd client
npm install

🌱 Future Enhancements

AI-powered resume suggestions

Resume ATS score analysis

Multiple language support

Cloud-based resume storage

Admin dashboard

🔐 Security Practices

JWT-based stateless authentication

Password hashing using bcrypt

Environment variables for secrets

Sensitive files excluded via .gitignore

🤝 Contributing

Contributions are welcome!
Fork the repository and submit a pull request for improvements or fixes.

📄 License

This project is licensed under the MIT License.

👨‍💻 Author

Lucky Kumar
Full-Stack Developer 
