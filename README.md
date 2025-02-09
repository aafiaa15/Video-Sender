# 📹 Real-Time Video Sending Application

## 🚀 Overview
This is a **real-time peer-to-peer video sending application** built using **WebRTC, WebSockets, Node.js, and React**. The application enables seamless media streaming from a sender to a receiver using WebRTC's **Peer Connection API**.

## 🛠️ Tech Stack
- **Frontend:** React, WebRTC (PeerConnection API)
- **Backend:** Node.js, WebSockets
- **Networking:** STUN/TURN Servers for NAT traversal

## ✨ Features
- **Real-time Peer-to-Peer Video Streaming** using WebRTC.
- **WebSocket-based Signaling Server** in Node.js to manage connections.
- **ICE Candidate Exchange** for reliable connectivity.
- **Optimized STUN/TURN Server Configurations** for better NAT traversal.

## 🏗️ Architecture
1. **Signaling (WebSocket Server in Node.js)**
   - `createOffer` → Establishes peer connections.
   - `createAnswer` → Responds to connection requests.
   - `addIceCandidate` → Handles ICE candidates for better connectivity.

2. **WebRTC (Frontend in React)**
   - Uses `RTCPeerConnection` API to establish media streaming.
   - Handles video stream capture and transmission.
   - Exchanges ICE candidates to improve connection stability.

## 🔧 Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/aafiaa15/Video-Sender.git)
cd video-sending-app
```

### 2️⃣ Backend Setup (Node.js WebSocket Server)
```sh
cd server
npm install
node server.js
```

### 3️⃣ Frontend Setup (React)
```sh
cd ../client
npm install
npm start
```

## 🔌 How It Works
1. **User A (Sender) starts a video session.**
2. **User B (Receiver) joins the session.**
3. **WebSocket Server handles signaling** (offer, answer, ICE candidates exchange).
4. **WebRTC establishes a direct peer-to-peer video connection.**



## 🎯 Future Enhancements
- Add **screen sharing** feature.
- Implement **multi-user conferencing**.
- Improve UI with **better error handling and connection status indicators**.

## 🤝 Contributing
Feel free to submit issues or pull requests if you want to contribute! 🚀

## 📜 License
This project is licensed under the **MIT License**.
