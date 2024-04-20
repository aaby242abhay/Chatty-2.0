# Chatty 2.0

Chatty 2.0 is a real-time chat application built with React.js for the frontend and Node.js, Express, and Socket.io for the backend. It uses JWT for authentication and MongoDB as a database. The application also leverages WebRTC for peer-to-peer communication.

## Features

- Real-time messaging
- User authentication
- Persistent messages with MongoDB
- Encrypted passwords with bcryptjs
- Peer-to-peer communication with WebRTC

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js
- MongoDB

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/chatty-2.0.git
```

2. Install NPM packages
```bash
npm install
```

3. Create a `.env` file in the root directory of the project and add the following:
```bash
DB_CONNECTION=your_mongodb_uri
TOKEN_SECRET=your_jwt_secret
```

4. Start the server
```bash
npm run start
```

## Running Tests

To run tests, use the following command:
```bash
npm run test
```

## Built With

- [React.js](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Socket.io](https://socket.io/)
- [MongoDB](https://www.mongodb.com/)
- [JWT](https://jwt.io/)
- [bcryptjs](https://www.npmjs.com/package/bcryptjs)
- [WebRTC](https://webrtc.org/)

