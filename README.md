# Chat Application

Simple real-time chat application built with a React frontend + Node/Express backend.

🚀 Features

Real-time one-to-one and group chat (via WebSockets / Socket.io)

User authentication & registration

Frontend UI built with React (hooks / context)

Backend API with Express + MongoDB for chat history and users

Modular structure with separate Frontend/ and Backend/ folders

🛠 Getting Started

1. Clone the repository --> 
git clone https://github.com/sayakroy83/chat-application.git  

2. Navigate into and install dependencies for both parts --> 
cd chat-application/Backend && npm install  
cd ../Frontend && npm install  

3. Set up your environment variables (e.g., MONGO_URI, JWT_SECRET, PORT)

4. Run server and client
 >>In Backend  
   npm run dev  
 >>In Frontend  
   npm start  

🧩 Project Structure
chat-application/
├─ Backend/        # Express server, socket setup, MongoDB models  
├─ Frontend/       # React app, UI components, context for auth & chat  
└─ .gitignore etc  
