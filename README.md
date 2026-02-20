# Swift Meet

Swift Meet is a real-time video conferencing web application built using **WebRTC**, **Socket.IO**, and **React**.  
It enables users to join video meetings instantly with features like video/audio toggle, screen sharing, and real-time chat — similar to modern platforms like Google Meet or Zoom.

---

## Features

- 🎥 Real-time video calling using WebRTC
- 🎙️ Audio mute / unmute
- 📷 Video on / off
- 🖥️ Screen sharing
- 💬 Real-time chat during meetings
- 🔔 Unread message counter
- 👥 Multi-user video conferencing
- 🔗 Unique meeting rooms via URL
- 🎨 Clean and responsive UI

---

## Tech Stack

### Frontend
- React.js
- Material UI (MUI)
- WebRTC
- Axios
- CSS 

### Backend
- Node.js
- Express.js
- Socket.IO
- Bcrypt
- Crypto

### Real-Time Communication
- WebRTC (Peer-to-Peer)
- STUN Servers (Google STUN)

---

## 🧠 Architecture Overview

- **WebRTC** handles peer-to-peer audio/video streaming.
- **Socket.IO** is used for:
  - Signaling (SDP & ICE exchange)
  - Chat messages
  - User join/leave events
- Each meeting room is identified by a **unique URL path**.