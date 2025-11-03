# Practice 2 - Authentication System (JWT Protected Routes)

##  Objective
Implement backend API authentication using **JWT (JSON Web Tokens)** to secure routes and restrict unauthorized access.

---

##  Features
- `/login` route validates user credentials and returns a JWT.
- `/protected` route accessible only with a valid token.
- Middleware checks for missing or invalid tokens.
- Token sent in the `Authorization` header as a **Bearer token**.

---

##  How to Run
1. Open project folder in VS Code or Nimbus.
2. Install dependencies:
   ```bash
   npm install
