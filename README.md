# Chat Application

This project implements a real-time chat application using the MERN stack. It includes user authentication, real-time messaging, and role-based access control.


## Features

### User Authentication
- Users can register and log in to their accounts.
- Authentication is securely handled using JWT tokens.

### Real-Time Messaging
- Instant messaging is powered by Socket.io, providing real-time communication between users.

### Online User Status
- Real-time online status updates are implemented using Socket.io and React Context, allowing users to see who is online.


### Error Handling
- Comprehensive error handling on both the server and client sides to ensure robustness and reliability.

## Application Workflow

### User Registration and Login
1. **Register**: Users can create a new account by providing necessary details.
2. **Login**: Users log into their accounts using their credentials.

### Messaging
1. **Real-Time Messaging**: 
   - Users can send and receive messages instantly.
   - Messages are transmitted in real-time using Socket.io.
2. **Online Status**: 
   - Users can see which of their contacts are online.
   - Online status is updated in real-time.

## Technologies Used

### Frontend
- **React**: A JavaScript library for building user interfaces.
- **React Router**: For client-side routing.
- **TailwindCSS**: A utility-first CSS framework for rapid UI development.
- **Daisy UI**: A plugin for TailwindCSS that provides UI components.

### Backend
- **Node.js**: A JavaScript runtime built on Chrome's V8 engine.
- **Express**: A minimal and flexible Node.js web application framework.
- **MongoDB**: A NoSQL database for storing user data and messages.
- **Socket.io**: A library for real-time web applications.



### Authentication
- **JWT (JSON Web Tokens)**: For secure authentication and authorization.

