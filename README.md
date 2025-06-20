# Authentication System - Prodigy Internship Task 1

This project was developed as part of the Full-Stack Development Internship at Prodigy InfoTech. It implements a complete authentication system with a secure backend and a modern React frontend.

## Project Overview

This is a full-stack authentication system that demonstrates secure user management with the following features:

- User registration with secure password handling
- User login with JWT authentication
- Protected routes for authenticated users
- Modern and responsive UI using React
- RESTful API backend using Node.js

## Project Structure

```
├── backend/               # Backend Node.js application
│   ├── controllers/      # Request handlers
│   ├── middleware/       # Authentication middleware
│   ├── models/          # Database models
│   ├── routes/          # API routes
│   └── services/        # Business logic
│
├── frontend/             # React frontend application
│   ├── src/
│   │   ├── components/  # Reusable React components
│   │   ├── context/     # React context for auth state
│   │   ├── pages/       # Page components
│   │   └── services/    # API service layer
│   └── public/          # Static assets
```

## Technologies Used

### Backend

- Node.js
- Express.js
- MongoDB (with Mongoose)
- JWT for authentication
- bcrypt for password hashing

### Frontend

- React
- Vite
- React Router
- Context API for state management

## Getting Started

1. Clone the repository
2. Install dependencies for both backend and frontend:

   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. Set up environment variables in `.env` file
4. Start the development servers:

   ```bash
   # Start backend server
   cd backend
   npm start

   # Start frontend development server
   cd frontend
   npm run dev
   ```

## Features

- Secure user registration and login
- Protected routes that require authentication
- JWT-based authentication
- Modern and responsive user interface
- Form validation
- Error handling

## Internship Information

This project was completed as Task 1 of the Full-Stack Development Internship at Prodigy InfoTech. The internship focuses on building real-world applications using modern web development technologies and best practices.

### Learning Outcomes

- Implementation of secure authentication systems
- Full-stack application architecture
- REST API development
- Modern React development practices
- State management in React applications
- Security best practices in web development

## Author

Developed as part of the Prodigy InfoTech Internship Program - Task 1
