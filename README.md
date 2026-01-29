# Secure Session-Based Authentication System
     A backend authentication system that securely manages User login using Server-side sessions. 
     The project focuses on preventing Unauthorized access and maintaining secure user state across requests.

---

## Features
   - User login and logout
   - Secure session creation and management
   - Session validation for protected resources
   - Automatic session invalidation on logout
   - Prevention of unauthorized access

---

## Tech Stack
   - Java
   - JDBC
   - MySQL
   
## Tools & Platform
   - Eclipse IDE
   - Github (Version Control)

---

## Authentication Workflow
   1. User enters login credentials and submits them
   2. Server checks whether credentials are correct or not
   3. After login, the Server creates Unique session
   4. User authentication state is stored securely on the server
   5. Only logged-in users are allowed to perform certain actions
   6. When the user logs out, the server deletes the session

---

## Security Implementation
   - Server-side authentication
   - Session-based authorization
   - Backend-controlled access validation

---

## Testing
   - Login validation testing
   - Session expiration testing
   - Unauthorized access checks

---

## How to Run
   1. Setup MySQL database
   2. Update database connection details
   3. Run the project in Eclipse

---

## Learning Outcome
   - Understanding session-based authentication
   - Secure backend access control
   - Real-world login system implementation
   - Writing structured backend documentation
