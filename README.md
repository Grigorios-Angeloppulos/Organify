
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

git clone [https://github.com/Grigorios-Angeloppulos/Organify.git](https://github.com/Grigorios-Angeloppulos/Organify.git)
cd Organify

---

### 2. Configure Environment Variables

Create a `.env` file inside the `backend` directory:

touch backend/.env

Add the following environment variables to `backend/.env`:

MONGO_URI=your_mongodb_connection_string
FPORT=your_frontend_port
EMAIL_SENDER=your_email_sender_address
EMAIL_PASS=your_email_password
SESSION_KEY=your_session_secret_key
JWT_KEY=your_jwt_secret_key

> ⚙️ **Prerequisites:**
> * Set up a **MongoDB** database.
> * Create an **EmailJS** account and configure an app email account to generate the required credentials.

---

### 3. Running the Application

Choose **one** of the options below to launch the application:

#### Option A: Using Docker *(Recommended)*
No need to install Node.js globally. Run the application in an isolated container:

# Build the Docker image from the project root
docker build -t my-app .

# Run the container
docker run -d -p 3000:3000 --env-file backend/.env --name my-running-app my-app

> ⚠️ **Docker Note:** Make sure your `.env` values do **not** use quotes (e.g., use `MONGO_URI=value`, not `MONGO_URI="value"`).

#### Option B: Local Setup (Node.js)
If you prefer running Node.js directly on your host machine:

# Install backend dependencies
cd backend
npm install
npm start


