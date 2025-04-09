# Full-Stack React: Kanban Board with JWT Authentication

## 📝 Overview

This project is a secure, full-stack Kanban board application built with React, Express, Sequelize, and PostgreSQL. It features authentication using **JSON Web Tokens (JWT)**, allowing users to securely log in and manage their tasks. The server verifies login requests and protects API routes using token-based authentication, while the frontend stores tokens in `localStorage` to persist sessions and secure user access.

This was built to fulfill Challenge #14 of the Full-Stack Bootcamp curriculum.

**🔗 Deployed on Render:** [(https://kanban-board-ymqk.onrender.com)]  
**💻 GitHub Repo:** [(https://github.com/karinuhgarcia/kanban_board)]

## Technologies Used
Frontend: React, Vite

Backend: Express.js, Sequelize ORM, PostgreSQL

Authentication: JSON Web Tokens (JWT), bcrypt

Deployment: Render

Testing: Insomnia (API testing)

## Setup Instructions
# Clone and Install Dependencies

git clone the repository
npm run install

# Create a .env in /server/

-DB_NAME=kanban_db
- DB_USER=your_postgres_username
- DB_PASSWORD=your_postgres_password
- JWT_SECRET_KEY=some_random_secret_key
- PORT=3001

# Seed the Database
npm run seed
This will initialize the database and populate users and tickets.

# Run the App (Development)
npm run start:dev
Starts backend at http://localhost:3001
npm run start
Starts frontend at http://localhost:5173

Karina Garcia
[in/-karinagarcia]
[https://github.com/karinuhgarcia]
