# Realtime White Board 🎨🖊️

> A real-time collaborative whiteboard web app that allows multiple users to draw and interact on the same canvas simultaneously.

---

## 🚀 Live Demo
(Add your deployed link here if available)

---

## 📌 Features

- 🎨 Real-time collaborative drawing
- 👥 Multiple users can join and draw together
- 🖌️ Adjustable brush size
- 🌈 Color selection
- 🧽 Eraser tool
- 🗑️ Clear canvas for all users
- ⚡ Instant synchronization using WebSockets
- 📱 Responsive design (Desktop & Mobile supported)

---

## 🛠️ Tech Stack

**Frontend**
- HTML
- CSS
- JavaScript
- Canvas API

**Backend**
- Node.js
- Express.js
- Socket.IO

---

## 📂 Project Structure

Realtime-white-board/
│
├── index.html
├── style.css
├── app.js
├── server.js
├── package.json
└── README.md

---

## 🧑‍💻 Installation & Setup

### 1️⃣ Clone the repository

git clone https://github.com/aftb777/Realtime-white-board.git

cd Realtime-white-board

---

### 2️⃣ Install dependencies

npm install

---

### 3️⃣ Run the server

node server.js

OR (if using nodemon)

npx nodemon server.js

---

### 4️⃣ Open in Browser

Visit:
http://localhost:3000

Open multiple tabs or devices on the same network to test real-time collaboration.

---

## 🔌 How It Works

- When a user draws on the canvas, drawing coordinates are captured.
- These coordinates are sent to the server using Socket.IO.
- The server broadcasts the drawing data to all connected clients.
- All users see updates instantly.

---

## 📡 Socket Events Used

- connection
- draw
- clear
- disconnect

---

## 📦 Deployment

You can deploy this project on:

- Render
- Railway
- Heroku
- Vercel (Frontend)
- Any VPS with Node.js support

Make sure WebSockets are enabled on your hosting platform.

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

## 👨‍💻 Author

Developed by Aftaab 🚀

If you like this project, give it a ⭐ on GitHub!

---

Happy Coding 💻🔥
