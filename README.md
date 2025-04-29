# Real-Time-Chat-Application

A simple real-time chat app supporting multiple users with message persistence, clear history, and login/logout functionality.

---

## 🚀 Features

- Real-time messaging between users
- Socket-based message delivery
- Message history persistence across sessions
- "Clear History" button to remove chat history (per user)
- Logout and login support without losing message history
- Clean and consistent UI (no unintended duplicates or UI shifts)

---

## 🧑‍💻 Tech Stack

- **Frontend:** React / Vite / Tailwind CSS (update if different)
- **Backend:** Node.js / Express / Socket.IO (update if different)
- **Database:** (e.g., MongoDB, Firebase) — used for message persistence

---

Install dependencies
Client:
  cd client
  npm install
  
Server:
  cd ../server
  npm install
  
Run the application
  Start server:
   cd server && node index.js

  Start client:
   cd client
    npm start

📋 Notes
Do not modify the UI layout. All fixes must preserve the original design strictly.

Ensure messages are shown only once for the sender and the receiver.

Message history must persist unless explicitly cleared using the "Clear History" button.
 
