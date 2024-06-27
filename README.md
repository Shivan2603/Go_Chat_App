# Futuristic Real-time Chat App

![Chat App Demo](demo.gif)

This GitHub repository hosts the source code for an advanced real-time chat application developed using Go for the backend and Angular for the frontend. Users can engage in real-time conversations, with messages appearing instantly as they are sent.

The backend of the application is crafted using Go, a robust programming language recognized for its speed and efficiency. It leverages the Gorilla WebSocket package to manage real-time communication between clients and the server.

On the other hand, the frontend of the application is constructed using Angular, a widely-used front-end development framework that offers robust tools for creating responsive and dynamic user interfaces. It integrates Socket.IO to handle real-time communication with the server and exhibit chat messages to users.

This repository serves as a solid groundwork for constructing a real-time chat application using Go and Angular, making it an invaluable resource for developers keen on exploring real-time application development with these cutting-edge technologies.

**Technology Stack:** Go, Angular

## Getting Started

Clone the project

```bash
  git clone https://github.com/bagasdisini/real-time-chat-app
```

Navigate to the project directory

```bash
  cd real-time-chat-app
```

### Backend Setup

Install dependencies

```bash
  cd backend
  go mod tidy
```

Launch the server

```bash
  go run .
```

### Frontend Setup

Install dependencies

```bash
  cd frontend
  npm install
```

Start the server

```bash
  npm start
```

Feel free to customize and enhance this futuristic chat application to meet your specific requirements and design preferences!