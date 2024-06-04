Simple User Authentication
This repository provides a basic implementation of user authentication, including registration, login, and password reset functionalities, using Node.js, Express, and PostgreSQL.

Technologies
Backend: Node.js, Express, PostgreSQL
Authentication: JWT (JSON Web Tokens)
Password Hashing: bcrypt
Installation
To get started with the project, follow these steps:

Clone the repository:
git clone https://github.com/NAMBIRAJA-M/your-repo-name.git

Install dependencies:
npm install
Set up environment variables:

Create a .env file in the backend directory and add the following:
PORT=5000
DATABASE_URL=your_postgresql_database_url

Start the backend server:
npm start

Usage
Register a new user via the /api/auth/register endpoint.
Log in with an existing user via the /api/auth/login endpoint.


API Endpoints
User Registration: POST /register
User Login: POST /login
