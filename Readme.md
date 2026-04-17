# 💬 Real-Time Chat Application

A real-time chat application built using **WebSockets**, enabling instant communication between users with low latency and efficient message delivery.

---

## 🚀 Tech Stack

### Frontend
- React (TypeScript)
- Vite (Bundler)
- Tailwind CSS

### Backend
- Node.js
- TypeScript
- WebSocket (ws)

---

## ✨ Features

- ⚡ Real-time messaging using WebSockets  
- 🧑‍🤝‍🧑 Room-based chat system (join specific rooms)  
- 📡 Persistent WebSocket connection  
- 🔄 Instant message broadcasting  
- 🎨 Clean and responsive UI with Tailwind CSS  
- ⚙️ Lightweight and fast build using Vite  

---

## 🧠 How It Works

- A WebSocket connection is established between client and server  
- Users join a specific room using a `join` event  
- Messages are sent using a `chat` event  
- Server broadcasts messages to all users in the same room  

---

## 📦 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/ujjawal396/chat-App.git
cd your-repo