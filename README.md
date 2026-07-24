
# 🚀 Full-Stack Web Application & Portfolio

Welcome to the official repository! This project features a modern full-stack application alongside an interactive portfolio showcasing custom 3D models, SVG animations, and full user/task management capabilities.

<img width="1917" height="677" alt="Στιγμιότυπο οθόνης 2025-09-04 183500" src="https://github.com/user-attachments/assets/c17f64a6-a8b3-4939-99c7-c252041f9a9c" />

✨ **Live Portfolio Demo:** https://organify.inteliseis.gr/
---

## 🛠️ Tech Stack

### **Frontend**
* **Markup & Styling:** HTML5, CSS3, [Tailwind CSS](https://tailwindcss.com/) 🎨
* **Scripting & Interactivity:** JavaScript (ES6+) ⚡
* **3D Graphics:** [Three.js](https://threejs.org/) *(inspired by DesignCourse's Three.js workflow)* 🌐
* **Client Email Services:** EmailJS 📧

### **Backend & Database**
* **Runtime:** Node.js 🟩
* **Database:** MongoDB Atlas (NoSQL) 🍃
* **Mailing Service:** Nodemailer 📨

### **Infrastructure & Security**
* **Deployment & Proxy:** IIS Server (Reverse Proxy) 🛡️
* **SSL/TLS:** Custom TLS Certificate for HTTPS

---

## 🌟 Highlights & Key Features

* 🎨 **Interactive 3D Graphics:** Dynamic 3D canvas built with Three.js.
* ⚡ **Custom SVG Animations:** Hand-crafted, code-driven SVG animations for unique UI transitions.
* 📬 **Dual Email Functionality:** Working EmailJS form on the client side, plus Nodemailer background scheduling and verification.
* 👥 **User & Task Management:** Complete database schema support for managing users, task scheduling, and group assignments.
* 📱 **Cross-Platform Ready:** Configurable endpoints suited for standard web browsers and mobile frameworks (e.g., React Native).

* ## 📦 Getting Started

### 1. Clone the Repository
git clone https://github.com/Grigorios-Angeloppulos/Organify.git
2.Add these enviromental variables: MONGO_URI,FPORT ,EMAIL_SENDER,EMAIL_PASS,SESSION_KEY,JWT_KEY<br/> **in the backend folder in a .env file**
You need to set up a mongo db database as well as an account in emailJS and an email account for the app and run relative credentials
If you dont want to install nodejs, you can run usinf  docker build -t my app in the project root


