# 💻 Code Wave

**Code Wave** is a real-time collaborative code editor built using **React**, **Node.js**, and **Socket.IO**. It allows multiple users to join the same coding session via a shared room ID and collaborate live in a seamless and synchronized coding environment.

---

## 🖼️ Screenshots

![Screenshot 2025-04-20 174612](https://github.com/user-attachments/assets/4b4e8316-74b1-4dad-8d02-041fbedada74)
![Screenshot 2025-04-20 174542](https://github.com/user-attachments/assets/9bfbd5d0-bdce-4a30-a72b-343a68dd2150)
![Screenshot 2025-04-20 174921](https://github.com/user-attachments/assets/0ccb0f09-ca7e-47f9-ad6e-6de3028db8f2)

---

## 🌐 Live Demo

🔗 Try the app live at: [https://code-wave-jet.vercel.app](https://code-wave-jet.vercel.app)

---

## ✨ Features

- 🔁 **Real-time Code Syncing** – Code changes are reflected instantly across all connected clients.
- 🔐 **Unique Room IDs** – Secure and easy-to-share room IDs for collaborative sessions.
- 🧠 **User-friendly Interface** – Clean, intuitive layout that focuses on productivity.
- 📋 **Clipboard Utility** – Quick copy functionality for room sharing.
- ⚛️ **Modern Stack** – Built using React, Node.js, Express, and Socket.IO for high performance.

---

## 📦 Tech Stack

**Frontend:**
- React
- React Router DOM
- React Hot Toast
- UUID

**Backend:**
- Node.js
- Express
- Socket.IO

---

## 📁 Project Structure

```
code-wave/
├── public/                # Static files and HTML template
├── src/
│   ├── components/        # Reusable UI components (Editor, Client)
│   ├── pages/             # Pages: Home & EditorPage
│   ├── socket.js          # Socket.IO client config
│   ├── Actions.js         # Defined socket action constants
│   └── App.js             # Main app routing
├── server.js              # Express and Socket.IO backend server
├── package.json           # Project metadata and scripts
└── README.md              # Project overview and documentation
```

---

## 🚀 Getting Started

Follow the steps below to run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/MananHere576/code-wave.git
cd code-wave
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start the Application

```bash
npm start
```

This will:
- Build the React frontend
- Launch the Node.js + Socket.IO backend on **localhost:5000**

---

## 🧪 Usage Guide

1. Open the app in your browser.
2. Enter your **username** on the homepage.
3. Either:
   - **Enter an existing Room ID** to join a session, or
   - **Click "Create New Room"** to generate a unique room.
4. Share the Room ID with collaborators.
5. Start editing together in real-time. Code updates will sync across all participants!

---

## 🛠 Environment Details

- Node version: `>=14.x`
- React scripts: `^5.0.1`
- WebSocket-based real-time communication via Socket.IO

---

## 🤝 Contributing

Contributions are welcome! 🙌

To contribute:
1. Fork the repo
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Commit (`git commit -am 'Add your message'`)
5. Push to the branch (`git push origin feature/your-feature`)
6. Open a Pull Request


---

## 🧑‍💻 Author

Built with ❤️ by **Manan Mishra**

- GitHub: [@MananHere576](https://github.com/MananHere576)
- Live Demo: [code-wave-jet.vercel.app](https://code-wave-jet.vercel.app)

