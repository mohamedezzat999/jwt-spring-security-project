# Spring Boot JWT Authentication (Spring Security 6.x)

A minimal Spring Boot 3.x project demonstrating how to implement JWT-based authentication using Spring Security 6.x.

## 🔐 Features

- User registration endpoint
- User authentication (JWT generation)
- Secured test endpoint (requires a valid JWT)
- Built with Java 21 and Spring Boot 3.x
- Stateless authentication using JSON Web Tokens (JWT)

---

## 📦 Tech Stack

- Java 21
- Spring Boot 3.x
- Spring Security 6.x
- JWT (via `jjwt` or similar library)
- Maven

---
🛡️ Security Notes
Passwords are hashed using BCrypt.

JWTs are signed with a secret key and have an expiration time.

Stateless session management with token verification on every request.
