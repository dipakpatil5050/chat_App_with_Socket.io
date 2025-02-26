# Chat App with Socket.IO

A real-time chat application built using **Node.js, Express, and Socket.IO**.

## Features

- **Real-time messaging** powered by WebSockets
- **Modern chat UI** inspired by mobile messaging apps
- **Message filtering** (users do not receive their own messages back)
- **Keyboard shortcut** (Press `Enter` to send messages)

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express, Socket.IO

## Screenshots

### App UI:

<img width="597" alt="image" src="https://github.com/user-attachments/assets/23c409a2-3f71-4b13-a2b3-7ed3eb33337d" />

### 2 Users Chatting

<img width="960" alt="image" src="https://github.com/user-attachments/assets/a8db34f7-e310-4200-a0bb-0f21e20f2430" />

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/dipakpatil5050/chat_App_with_Socket.io.git
   cd chat-app
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the server:
   ```sh
   node server.js
   ```
4. Open `http://localhost:3000` in your browser.

## How It Works

- Users enter messages in the chat input.
- Messages are sent to the server via **Socket.IO** and broadcast to other users.
- The sender does not receive their own message back.
- Messages appear instantly in a **mobile-like UI**.

## License

This project is open-source under the **MIT License**.
