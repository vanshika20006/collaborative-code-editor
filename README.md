# 🚀 Collaborative Code Editor

A real-time collaborative code editor built with React, Monaco Editor, Yjs, Socket.IO, and Node.js. Multiple users can join a shared coding session and edit code simultaneously with instant synchronization across all connected clients.

---

## ✨ Features

- 👥 Multi-user collaboration
- ⚡ Real-time code synchronization
- 📝 Monaco Editor integration
- 🔄 Conflict-free editing using Yjs
- 🌐 WebSocket communication with Socket.IO
- 📋 Connected users list
- 🚀 Dockerized deployment
- 📱 Responsive and modern UI

---

## 🛠️ Tech Stack

### Frontend
- React
- Monaco Editor
- Yjs
- Socket.IO Client

### Backend
- Node.js
- Express.js
- Socket.IO
- Y-Socket.IO

### DevOps
- Docker
- Render

---

## 📂 Project Structure

```bash
├── Frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── Backend/
│   ├── server.js
│   ├── public/
│   └── package.json
│
└── Dockerfile
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/vanshika20006/collaborative-code-editor.git
cd collaborative-code-editor
```

---

## Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```

Frontend will run on:

```bash
http://localhost:5173
```

---

## Backend Setup

```bash
cd Backend
npm install
npm run dev
```

Backend will run on:

```bash
http://localhost:3000
```

---

## 🐳 Docker Setup

Build Docker Image:

```bash
docker build -t collaborative-editor .
```

Run Container:

```bash
docker run -p 4000:3000 collaborative-editor
```

Application:

```bash
http://localhost:4000
```

---

## 🌍 Deployment

This application is containerized using Docker and can be deployed on:

- Render
- Railway
- AWS ECS
- AWS EC2
- DigitalOcean
- Fly.io

### Render Deployment

1. Push project to GitHub
2. Create a new Web Service on Render
3. Connect GitHub repository
4. Render automatically detects the Dockerfile
5. Deploy

---

## 🔍 Health Check

Backend provides a health endpoint:

```http
GET /health
```

Response:

```json
{
  "message": "ok",
  "success": true
}
```

---

## 🔄 How It Works

1. User enters a username and joins the editor.
2. Socket.IO establishes a real-time connection.
3. Yjs manages shared document state.
4. Monaco Editor displays the synchronized code.
5. Changes made by any user are instantly propagated to all connected clients.

---

## 🎯 Learning Outcomes

This project demonstrates:

- Real-time communication using WebSockets
- Collaborative editing with CRDTs (Yjs)
- Frontend-backend integration
- Docker containerization
- Cloud deployment workflows
- Modern React development

---

## 📸 Screenshots

Add project screenshots here.

---

## 👩‍💻 Author

**Vanshika Sharma**

- Full Stack Developer
- MERN Stack Developer
- AI & Cloud Enthusiast

---
