![logo](https://github.com/omk18p/code-sync/assets/100127570/d1ff7f52-a692-4d51-b281-358aeab9156e)

A collaborative, real-time code editor where users can seamlessly code together. It provides a platform for multiple users to enter a room, share a unique room ID, and collaborate on code simultaneously.

![GitHub contributors](https://img.shields.io/github/contributors/omk18p/code-sync?style=for-the-badge&color=48bf21)
![GitHub Repo stars](https://img.shields.io/github/stars/omk18p/code-sync?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/omk18p/code-sync?style=for-the-badge&color=d7af2d)
![GitHub pull requests](https://img.shields.io/github/issues-pr/omk18p/code-sync?style=for-the-badge&color=f47373)
![GitHub License](https://img.shields.io/github/license/omk18p/code-sync?style=for-the-badge&color=e67234)
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fomk18p%2Fcode-sync&label=Repo%20Views&countColor=%2337d67a&labelStyle=upper)

---

## 🔮 Features

- 💻 Real-time collaboration on code editing across multiple files
- 📁 Create, open, edit, save, delete, and organize files and folders
- 💾 Download the entire codebase as a ZIP
- 🚀 Unique room generation with room ID
- 🌍 Multi-language support & syntax highlighting
- ⚡ Code execution via Piston API
- 🔄 Live sync of all changes
- 📢 Join/leave notifications
- 👥 Online/offline user list
- 💬 Real-time chat
- 🎩 Tooltip showing active editors
- 💡 Language-based auto-suggestions
- 🔠 Font size & family customization
- 🎨 Multiple themes
- 🖊️ Collaborative drawing board
- 🤖 AI Copilot for generating/editing code

---

## 🚀 Live Preview

Try the live version: [https://code-sync-live.vercel.app](https://code-sync-live.vercel.app)

---

## 💻 Tech Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![ExpressJS](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![Socket io](https://img.shields.io/badge/Socket.io-ffffff?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## ⚙️ Installation Guide

### 📥 Manual Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/omk18p/code-sync.git
   cd code-sync

## ⚙️ Installation Guide

### 📥 Step 2: Create `.env` Files

Create the following environment variable files manually:

#### 📁 `client/.env`
```env
VITE_BACKEND_URL=http://localhost:3000
```

#### 📁 `server/.env`
```env
PORT=3000
```

---

### 📦 Step 3: Install Dependencies

Install all required packages using npm:

#### 🔧 Frontend
```bash
cd client
npm install
```

#### 🔧 Backend
```bash
cd ../server
npm install
```

---

### 🚀 Step 4: Start the Application

Run the servers:

#### ▶️ Backend
```bash
cd server
npm run dev
```

#### ▶️ Frontend
```bash
cd ../client
npm run dev
```

---

### 🌐 Step 5: Open in Browser

Visit the following URL in your browser:

```
http://localhost:5173/
```

You're now ready to collaborate in real-time!

---

## 🐳 Docker Installation (Optional)

### 🐳 Step 1: Install Docker Desktop

Download Docker from:  
[https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop)

Then verify:
```bash
docker --version
```

---

### 🐳 Step 2: Pull Docker Images

```bash
docker pull omk18p/code-sync-server:latest
docker pull omk18p/code-sync-client:latest
```

---

### 🐳 Step 3: Run Docker Containers

```bash
# Start Backend on port 3000
docker run -d -p 3000:3000 --name code-sync-server omk18p/code-sync-server:latest

# Start Frontend on port 5173
docker run -d -p 5173:5173 --name code-sync-client omk18p/code-sync-client:latest
```

---

### 🌍 Step 4: Access in Browser

Open:
```
http://localhost:5173/
```

Everything should be live and ready!
