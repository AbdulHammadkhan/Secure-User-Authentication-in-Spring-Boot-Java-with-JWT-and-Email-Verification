Secure User Authentication in Spring Boot(Java) with JWT and Email Verification
This repository demonstrates how to set up a secure user authentication system in a Java-based Spring Boot application. It includes key features like user registration, login, and email verification using JWT (JSON Web Tokens), along with comprehensive security configurations via Spring Security.

-User Registration and Login with JWT (JSON Web Tokens) for authentication.
-Email Verification for account activation.
-Essential security configurations using Spring Security to protect the application.
-Integration with Supabase Database for user storage.

Key Features
Sign-Up and Log-In System: Allows users to create accounts and log in securely.
Email Verification: Sends email verification links to activate user accounts using Java Mail Sender.
JWT Authentication: Validates and manages secure tokens for user sessions.
Robust Security Configurations: Configures CORS, authentication providers, and request filters using Spring Security.
No UI Included: All endpoints are tested using Postman for simplicity.

Dependencies
Spring Boot (Spring Security, Spring Web, Spring Data JPA)
PostgreSQL Driver (Database)
Lombok (For getters and setters)
Java Mail Sender (For email functionality)
Supabase Database (User data storage)

Step-by-Step Functionality
Setup: Configure dependencies and integrate necessary tools like Supabase and Google App Passwords for email.
Authentication: Implement JWT generation and validation, extracting claims and validating tokens securely.
Security Configuration: Define authentication providers, configure CORS, and set up request filters.
Email Verification: Enable users via email with HTML-styled verification messages.
Testing: Verify all functionality using Postman. 
