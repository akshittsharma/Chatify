## Chatify

Chatify is a real-time messaging application designed for seamless communication. With features like instant messaging, group chats, multimedia sharing, and more, Chatify provides a robust platform for personal and professional communication.

## Features

- Real-time messaging: Engage in live chat conversations with other users.
- Online users display: See a list of users who are currently online.
- Responsivity: The app is designed to work seamlessly on all devices, including desktops, tablets, and mobile devices.
- Modern and simple design: The user interface is clean and intuitive, providing a smooth and enjoyable chat experience.

## Tech Stack

- Frontend: React
- Backend: Node.js and Express
- Database: MongoDB
- Real-time communication: Socket.IO

## Prerequisites

- Node.js and npm installed on your machine
- MongoDB database connection

## Installation

1. Clone the repository:

 

2. Install the dependencies:

   ````bash
   cd Chat.io/client && npm install
   cd Chat.io/server && npm install
   cd Chat.io/socket && npm install

3. Create a `.env` file in the server directory and provide the following environment variables:

   ````plaintext
   MONGODB_URI=<your-mongodb-connection-uri>
   PORT = 5000
   JWT_SECRET =<secret_code>
   JWT_EXP = 30d

4. Start the development server in socket/server/client:

   ````bash
   npm run dev

5. Open your browser and visit `http://localhost:5173` to access the chat.io application.

## Folder Structure

The project structure is organized as follows:

- `client`: Contains the React frontend code.
- `server`: Contains the Node.js and Express backend code.
- `socket`: Contains the Socket.io configuration.



## Acknowledgements

- [Socket.IO](https://socket.io/)
- [Create vite@latest](https://vitejs.dev/guide/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)

Enjoy using Chat.io!
