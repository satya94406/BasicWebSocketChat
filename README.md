**Real-Time Chat Application**
A simple real-time chat application built with Node.js, Express, and Socket.IO. This application allows multiple users to send and receive messages instantly using WebSocket communication.

**📌 Features**
Real-time bi-directional communication
Lightweight and fast
Simple UI with instant message display
Express.js for backend server handling
Socket.IO for real-time WebSocket communication

**🚀 Getting Started**

1. Clone the repository
   bash
   Copy
   Edit
   **git clone** https://github.com/yourusername/realtime-chat-app.git
   cd realtime-chat-app
2. Install Dependencies
   bash
   Copy
   Edit
   npm install
3. Start the Server
   bash
   Copy
   Edit
   node server.js
4. Open in Browser
   Navigate to http://localhost:5000 in your browser.

**⚙️ How It Works**
**Backend (server.js):**
Sets up an Express server and serves static files from the public folder.
Integrates Socket.IO for real-time communication.
Listens for the event "user-message" and broadcasts it to all connected clients.

**Frontend (index.html):**
Connects to the Socket.IO server.
Sends messages to the server when the "Send" button is clicked.
Listens for "message" events and displays them in the chat window.

**🌐 Dependencies**
Express: Fast, unopinionated, minimalist web framework for Node.js
Socket.IO: Enables real-time, bidirectional communication
HTTP: Core Node.js module for server creation

**✨ Future Improvements**
🔐 User Authentication - Secure user login and session handling
👥 Display Usernames with Messages - Show who sent the message
💅 Improve UI Design - Modern, responsive design
📩 Private Messaging - Enable one-to-one communication
