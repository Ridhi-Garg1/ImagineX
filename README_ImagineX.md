# 🧠ImagineX – Full Stack AI SaaS Image Generator

**ImagineX** is a modern full-stack SaaS application that allows users to generate stunning images from text prompts using the **Clipdrop API**. Built with the **MERN Stack**, this platform offers a seamless AI-driven experience with secure authentication, a credit-based usage system, and integrated online payments.

> 💡 Turn your ideas into visuals — instantly powered by AI.

---

## 🌐 Live Demo

🚀 https://imaginex-1.onrender.com/

---

## 🎯 Why ImagineX Stands Out

- ✨ **AI-Powered Image Generation** – Instantly create visuals using the Clipdrop API.
- 🔐 **Secure Authentication** – Built with robust JWT-based login system.
- 💳 **Credit System** – Users can purchase and use credits to generate images.
- ⚙️ **Full SaaS Workflow** – Built to scale, with secure backend and smooth frontend.
- 🛠️ **Real-Time Processing** – Instant feedback and image generation.
- 🌍 **Modern Deployment-Ready Architecture**

---

## 🧰 Tech Stack

| Layer         | Technologies                          |
|---------------|----------------------------------------|
| Frontend      | React.js, Tailwind CSS                 |
| Backend       | Node.js, Express.js                    |
| Database      | MongoDB Atlas                          |
| Authentication| JWT, bcrypt                            |
| AI API        | Clipdrop API                           |
| Payments      | Online Payment Gateway                 |
| Deployment    | Vercel / Render (Optional)             |

---

## 🛠️ Local Setup Instructions

> Open **two terminals** in VS Code — one for `client`, one for `backend`.

### 🔹 Frontend (Client Side)

```bash
cd client
npm install
npm run dev
```

### 🔹 Backend (API Server)

```bash
cd backend
npm install
npm run server
```

---

## 🔐 Environment Variables

Create a `.env` file inside the `backend/` directory and add the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key

CLIPDROP_API_KEY=your_clipdrop_api_key
STRIPE_SECRET_KEY=your_stripe_secret_key
```

> 🧠 You can get your Clipdrop API key from: [https://clipdrop.co/apis/](https://clipdrop.co/apis/)

---

## ✨ Features Breakdown

### 👤 User Features

- Sign up and log in with secure authentication
- Generate AI images from text
- View history of generated images
- Purchase credits via payment gateway

### 🧰 Backend Features

- Full RESTful API with Express.js
- JWT-based auth and session handling
- Integration with Clipdrop API for AI generation
- Razorpay integration for secure credit purchases
- Credit tracking and user role management
- MongoDB for data persistence (users, credits, images)

---

## 📦 Key Dependencies

- **Frontend:** React, Tailwind CSS, axios, react-router-dom
- **Backend:** Express, Mongoose, bcrypt, JWT,Razorpay
- **AI:** Clipdrop API
- **Database:** MongoDB Atlas

---

## 👨‍💻 Author & Contact

**🧑‍💻 Author:** Ridhi Garg  
📧 Email: (mailto:ridhigargofficial20@gmail.com)  
🔗 LinkedIn: https://www.linkedin.com/in/ridhi-garg-69292a359/

---

## 🤝 Open to Collaboration

I’m actively exploring new opportunities as a **Full Stack Developer**. If you're building something exciting or hiring for your tech team, feel free to reach out!
