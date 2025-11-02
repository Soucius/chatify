# Chatify 💬

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Chatify is a full-stack, real-time chat application that allows users to connect and communicate with each other instantly. It features a modern, responsive user interface and is built with a robust backend to handle messaging, user authentication, and real-time updates.

**Live Demo:** [https://chatify-b55ks.sevalla.app/](https://chatify-b55ks.sevalla.app/)



## ✨ Features

- **Real-Time Messaging:** Instantaneous message delivery and updates using WebSockets.
- **User Authentication:** Secure user registration and login system.
- **Online User Status:** See which users are currently online.
- **Typing Indicators:** Know when someone is typing a message in your chat.
- **User Profiles:** View your profile with your username and avatar.
- **One-on-One Conversations:** Select a user from the list to start a private chat.
- **Responsive Design:** A clean and modern UI that works on both desktop and mobile devices.
- **Light/Dark Mode:** Toggle between light and dark themes for your viewing comfort.

## 🛠️ Tech Stack

Chatify is built with a modern technology stack:

*   **Frontend:**
    *   [React.js](https://reactjs.org/) - A JavaScript library for building user interfaces.
    *   [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework for rapid UI development.
    *   [daisyUI](https://daisyui.com/) - A component library for Tailwind CSS.
    *   [Socket.IO Client](https://socket.io/docs/v4/client-api/) - For real-time, bidirectional event-based communication.

*   **Backend:**
    *   [Node.js](https://nodejs.org/) - A JavaScript runtime built on Chrome's V8 JavaScript engine.
    *   [Express.js](https://expressjs.com/) - A minimal and flexible Node.js web application framework.
    *   [MongoDB](https://www.mongodb.com/) - A cross-platform document-oriented database program.
    *   [Socket.IO](https://socket.io/) - For enabling real-time, bidirectional and event-based communication.
    *   [JSON Web Tokens (JWT)](https://jwt.io/) - For secure user authentication.

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have the following installed on your machine:
*   [Node.js](https://nodejs.org/en/download/) (v14 or newer)
*   [npm](https://www.npmjs.com/get-npm) or [Yarn](https://classic.yarnpkg.com/en/docs/install/)
*   [MongoDB](https://docs.mongodb.com/manual/installation/) (or a MongoDB Atlas account)

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/chatify-app.git
    cd chatify-app
    ```

2.  **Install backend dependencies:**
    ```sh
    cd backend
    npm install
    ```

3.  **Install frontend dependencies:**
    ```sh
    cd ../frontend
    npm install
    ```

4.  **Configure Environment Variables:**

    In the `backend` directory, create a `.env` file and add the following environment variables. Replace the placeholder values with your actual configuration.

    ```env
    # .env in /backend
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    ```

### Running the Application

1.  **Start the backend server:**
    From the `/backend` directory, run:
    ```sh
    npm start
    ```
    The server will start on the port you specified (e.g., `http://localhost:5000`).

2.  **Start the frontend development server:**
    From the `/frontend` directory, run:
    ```sh
    npm start
    ```
    The application will open in your browser at `http://localhost:3000`.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
