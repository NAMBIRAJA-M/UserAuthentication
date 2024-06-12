# Simple User Authentication

This repository provides a basic implementation of user authentication, including registration, login, and password reset functionalities, using Node.js, Express, and PostgreSQL.

## Technologies

- **Backend:** Node.js, Express, PostgreSQL
- **Authentication:** JWT (JSON Web Tokens)
- **Password Hashing:** bcrypt

## Installation

To get started with the project, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/NAMBIRAJA-M/UserAuthentication.git
    ```

2. **Install dependencies:**

    ```bash
    cd UserAuthentication
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env` file in the backend directory and add the following:

    ```plaintext
    PORT=5000
    DATABASE_URL=your_postgresql_database_url
    ```

4. **Start the backend server:**

    ```bash
    npm start
    ```

## Usage

- **Register a new user** via the `/api/auth/register` endpoint.
- **Log in with an existing user** via the `/api/auth/login` endpoint.

## API Endpoints

- **User Registration:** `POST /register`
- **User Login:** `POST /login`
