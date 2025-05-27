--

# Backend Developer Test – User Authentication API

Project Overview

This is a backend coding challenge for a live collaboration project with a frontend developer. The goal is to build a secure, well-structured authentication system to support the following flows from the provided Figma design:

* User Registration
* Login
* Password Reset via OTP
* Email Verification

---

## Features to Implement

* User registration with:

  * First name, last name, email, password, address, phone (with internationalization)
* Email/password login
* Password reset flow:

  * Request reset via email
  * Verify email with OTP
  * Set and confirm new password
* Email verification (OTP-based)
* Secure password hashing
* Token/session management
* Role-based access control (optional)
* RESTful API design with consistent JSON responses

---

## Tech Stack

Please document the language, framework, and database you choose below:

* **Language**:
* **Framework**:
* **Database**:
* **Auth Strategy**: JWT or session-based (include reasoning below)

---

## Setup Instructions

Provide setup instructions below to help reviewers run your project locally.

```bash
# Clone the repo
git clone https://github.com/yourusername/project-name.git

# Navigate into the project directory
cd project-name

# Install dependencies
[command here, e.g., npm install]

# Copy environment variables
cp .env.example .env

# Add your local configuration
[Fill in .env content as needed]

# Run the application
[command here, e.g., npm run dev]

# (Optional) Run migrations or seed database
[command here, if applicable]
```

---

## API Documentation

You may document your core endpoints here or link to an external tool like Postman, Swagger, or Insomnia.

Example structure:

### POST /api/auth/register

Registers a new user.

**Request Body:**

```json
{
  "firstName": "John",
  "lastName": "Doe",
  "email": "john@example.com",
  "password": "SecurePass123!",
  "address": "123 Main St",
  "phone": "+233501234567"
}
```

**Response:**

```json
{
  "success": true,
  "message": "Registration successful. Please verify your email.",
  "data": { ... }
}
```

---

## Environment Variables

Include required variables with descriptions:

```
PORT=3000
DB_URI=your_database_connection
JWT_SECRET=your_jwt_secret
EMAIL_API_KEY=key_for_email_sending
OTP_EXPIRATION_MINUTES=5
```

---

## Notes

* Explain any assumptions, limitations, or shortcuts taken.
* Include links to any additional tools or libraries used.
* If any features are partially complete or not implemented, indicate that clearly.

---