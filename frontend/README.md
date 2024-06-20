# PrioritySetter

PrioritySetter is a full-stack MERN (MongoDB, Express, React, Node.js) application for managing priorities or tasks. It allows users to add, edit, and delete priorities, providing a seamless user experience.

# Technologies Used
# Backend
Node.js and Express: Server-side framework and runtime environment
MongoDB and Mongoose: Database and ODM (Object Data Modeling)
bcryptjs: Password hashing for enhanced security
jsonwebtoken: JSON Web Token (JWT) authentication
dotenv: Environment variable management
express-async-handler: Middleware to handle asynchronous functions
# Frontend
React: Frontend framework for building user interfaces
React Router DOM: Routing library for React
Redux Toolkit and React-Redux: State management tools for React applications
axios: HTTP client for making API requests
react-icons: Icons for React applications
react-toastify: Notification library for React
react-scripts: Scripts and tools for React apps (used for build, start, test, etc.)
Web Vitals: Tooling for measuring Core Web Vitals metrics
# Features
Authentication: Secure user authentication using JWT tokens.
CRUD Operations: Create, Read, Update, and Delete priorities.
Responsive Design: Supports desktop and mobile devices.
Error Handling: Comprehensive error handling for better user experience.
Testing: Includes unit and integration tests using Jest and React Testing Library.
Getting Started
# Prerequisites
Node.js and npm installed on your machine
MongoDB Atlas account or local MongoDB server
# Installation
Clone the repository: 
git clone https://github.com/Animace/PrioritySetter.git
cd PrioritySetter
Install dependencies:

bash
Copy code
# Install backend dependencies
npm install

# Install frontend dependencies
cd client
npm install
cd ..
Set up environment variables:

Create a .env file in the root directory with the following variables:

makefile
Copy code
NODE_ENV=development
PORT=
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
Usage
Start the backend server:

bash
Copy code
npm run dev
This command will concurrently start the backend server (using nodemon for hot-reloading) and the React frontend.

Open your browser and navigate to http://localhost:#### to use the application.

Contributing
Contributions are welcome! Fork the repository and submit a pull request for any enhancements or bug fixes.

License
This project is licensed under the ISC License - see the LICENSE file for details.

Acknowledgments
MongoDB
Express
React
Node.js
