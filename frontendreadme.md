# Frontend Developer Challenge

This is a live technical challenge for a frontend developer position at TG Holdings GH. You will implement authentication screens and a basic product listing interface, working collaboratively with a backend developer.

## 📌 Objective

Build a responsive and user-friendly frontend application based on the provided Figma design. The project includes API integration for authentication and product display.

---

## 🔧 Tech Stack

You may choose any of the following (or similar please indicate what framework you worked with):

- **Framework**: React, Vue, Svelte, SolidJS
- **Styling**: TailwindCSS (recommended), SCSS, CSS Modules
- **HTTP Client**: Axios or Fetch API
- **Optional**:
  - Form validation libraries (React Hook Form, VeeValidate)
  - State management (Context API, Redux, Pinia)

---

## 📱 Screens to Implement

### 1. Sign Up
- Fields: First Name, Last Name, Email, Password, Confirm Password, Address, Phone (international format)
- Validations: Required fields, password match, proper formats

### 2. Login
- Fields: Email, Password
- Handles authentication and error states

### 3. Password Reset
- Step 1: Email input for OTP
- Step 2: Enter OTP code
- Step 3: New password + confirmation

### 4. Landing Page
- Display user welcome message
- Logout functionality

### 5. Product Listing
- Display a list/grid of products from API or mock JSON
- Include product name, price, short description

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/yourusername/frontend-auth-test.git
cd frontend-auth-test

# Install dependencies
npm install

# Run development server
npm run dev
