# 💬 MERN Real-Time Chat Application

A full-stack real-time chat application that enables **instant one-on-one messaging** with secure authentication, a clean UI, and real-time updates using WebSockets.

Built using the **MERN stack**, styled with **Tailwind CSS** and **DaisyUI**, and powered by **Socket.IO** for real-time communication.

---

## 🚀 Live Demo
https://yappster-mern-chat-app-1.onrender.com/login

---

## 🧠 Features

- 🔐 User Authentication (Register & Login)
- 💬 Real-time One-on-One Messaging
- 🧑‍💻 Online/Offline User Status Indicators
- 💾 Persistent Chat History using MongoDB
- 📱 Responsive UI (Mobile-Friendly)
- 🚀 Real-time updates with Socket.IO

---

## 🛠 Tech Stack

| Layer         | Technologies                             |
|--------------|-------------------------------------------|
| Frontend     | React.js, Tailwind CSS, DaisyUI, Axios    |
| Backend      | Node.js, Express.js, Socket.IO            |
| Database     | MongoDB (Mongoose ODM)                    |
| Authentication | JWT (JSON Web Tokens)                  |
| API Testing  | Insomnia / Postman                        |
| Styling      | Tailwind CSS + DaisyUI                    |

---

## 🔁 Backend Architecture

- Backend built on **Express.js**, serving RESTful APIs.
- **MongoDB** stores user and message data.
- Used **Mongoose schemas** to define Users and Messages.
- **Socket.IO** handles:
  - Real-time messaging
  - Private room-based message delivery
  - Online/offline status updates
- Used **JWTs** to secure protected routes and socket connections.
- All APIs tested using **Insomnia** with proper status codes and error handling.

---

## 🖥 Screenshots

<img width="1897" height="850" alt="Screenshot 2025-07-20 101830" src="https://github.com/user-attachments/assets/2a395e59-4d74-46de-97d8-8c960f4c0dbd" />

<img width="1888" height="900" alt="Screenshot 2025-07-20 102313" src="https://github.com/user-attachments/assets/7332ece9-982e-4e13-b282-8d8073ff151b" />

<img width="1894" height="871" alt="Screenshot 2025-07-20 102047" src="https://github.com/user-attachments/assets/47543906-86f5-4294-b8a3-814e218fcc36" />

<img width="1911" height="912" alt="Screenshot 2025-07-20 102002" src="https://github.com/user-attachments/assets/7264da74-87f1-4598-884e-418e09efa177" />

<img width="1905" height="896" alt="Screenshot 2025-07-20 101924" src="https://github.com/user-attachments/assets/51a453a3-3d03-4d2f-b968-0f4de363cc3c" />

<img width="1917" height="868" alt="Screenshot 2025-07-20 101859" src="https://github.com/user-attachments/assets/80bb7566-66fc-4d36-aef8-3085a492c308" />

---

## 📦 How to Run the Project Locally

### 📌 Prerequisites
- Node.js (v16+)
- MongoDB (Atlas or local)
- Git

### 🔧 Backend Setup

```bash
cd backend
npm install


