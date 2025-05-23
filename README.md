# 📷 Live Camera Stream

This is a full-stack **Live Camera Streaming** application built using **Node.js** and **Express.js** on the backend, and **HTML, CSS, and JavaScript** on the frontend.

It captures real-time video from the user's webcam and streams it on the browser using modern browser APIs.

---

## 🚀 Live Demo

🌐 Frontend: [live-camera.netlify.app]

---

## 🧠 About This Project

This project demonstrates how to access a user's webcam and display the video feed live on the web page. It also shows how Node.js can serve the frontend and support future backend integrations like saving screenshots or applying real-time filters.

---

## 🛠 Technologies Used

- **Frontend**:  
  - HTML5 (for structure)  
  - CSS3 (for styling)  
  - JavaScript (for webcam integration using `getUserMedia()`)

- **Backend**:  
  - Node.js  
  - Express.js (for serving static files and handling potential API requests)

---

## 📹 How It Works

1. When the user opens the web page, the browser asks for camera access.
2. On permission granted, the app uses the `navigator.mediaDevices.getUserMedia()` API to access the webcam.
3. The video stream is displayed in a `<video>` tag in real-time.
4. The backend (Node + Express) serves the static frontend files and can be extended for advanced features like:
   - Capturing frames
   - Saving images to the server
   - Real-time processing using WebSockets or WebRTC

---
