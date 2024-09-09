# MERN Authentication System

This project is an authentication system built using the MERN stack (MongoDB, Express, React, Node.js). It features sign-up, login, and email verification functionalities. Custom emails for verification and welcome messages are sent using Mailtrap.

## Features

- User Registration (Sign-up)
- User Login
- Email Verification (using Mailtrap)
- Custom Welcome Emails
- Password Hashing (bcrypt)
- JWT Authentication
- Protected Routes

## Tech Stack

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Token (JWT)
- **Email Service**: Mailtrap for email testing

## Project Structure

```bash
📦mern-authentication
 ┣ 📂client (React Frontend)
 ┃ ┣ 📂public
 ┃ ┣ 📂src
 ┃ ┃ ┣ 📂components
 ┃ ┃ ┣ 📂pages
 ┃ ┃ ┣ 📜App.js
 ┃ ┃ ┗ 📜index.js
 ┣ 📂server (Node.js Backend)
 ┃ ┣ 📂config
 ┃ ┣ 📂controllers
 ┃ ┣ 📂models
 ┃ ┣ 📂routes
 ┃ ┣ 📜server.js
 ┗ 📜README.md
