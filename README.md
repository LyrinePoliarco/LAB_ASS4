# User Login Exceptions

This project implements a simple user login system in Java, demonstrating the use of custom exceptions to handle login-related errors. The program allows users to attempt login with a predefined password and limits the number of login attempts to three. If the user exceeds the maximum allowed attempts or enters an invalid password, custom exceptions are thrown to handle these scenarios.

## Problem Description

The task is to create two custom exceptions to handle the following login-related errors:

1. **MaxLoginAttemptsExceededException**: This exception is thrown when a user exceeds the maximum allowed login attempts (three attempts).
2. **InvalidPasswordException**: This exception is thrown when a user enters an invalid password.

The valid password for login is set to "password".

## Solution Steps

To solve the problem, follow these steps:

1. Create two custom exceptions in Java:
   - `MaxLoginAttemptsExceededException.java` to handle maximum login attempts exceeded.
   - `InvalidPasswordException.java` to handle invalid passwords.
2. Implement the `UserLogin.java` class to manage the user login process and validate the password.
3. Create a main class (`Main.java`) to prompt the user for input and handle exceptions thrown during the login process.
4. Thoroughly test the program to ensure it handles all specified conditions correctly.
5. Create a GitHub repository for the project.
6. Upload the Java files to the repository and add a `readMe.md` file with this description.
7. Commit and push your changes to GitHub.
8. Share the repository's URL link as the solution to the assignment.

## Repository Structure

```
/user-login-exceptions
    ├── src
    │   ├── MaxLoginAttemptsExceededException.java
    │   ├── InvalidPasswordException.java
    │   ├── UserLogin.java
    │   └── Main.java
    └── readMe.md
```

## Usage

To use the program, compile and run the `Main.java` class. Follow the prompts to enter the password and observe the exception handling for maximum login attempts and invalid passwords.
