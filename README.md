# User Login Exceptions

This project implements a simple user login system in Java, demonstrating the use of custom exceptions to handle login-related errors. The program allows users to attempt login with a predefined password and limits the number of login attempts to three. If the user exceeds the maximum allowed attempts or enters an invalid password, custom exceptions are thrown to handle these scenarios.

## Problem Description

The task is to create two custom exceptions to handle the following login-related errors:

1. **MaxLoginAttemptsExceededException**: This exception is thrown when a user exceeds the maximum allowed login attempts (three attempts).
2. **InvalidPasswordException**: This exception is thrown when a user enters an invalid password.

The valid password for login is set to "password".


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

## 1st SAMPLE OUTPUT 
```java
Enter password: Password123
Invalid password. You have 2 attempts left.

Enter password: P@ssw0rd
Invalid password. You have 1 attempts left.

Enter password: password
Maximum login attempts exceeded.

## 2nd SAMPLE OUTPUT

Enter password: lyrine 
Invalid password. You have 2 attempts left.

Enter password: poliarco
Invalid password. You have 1 attempts left.

Enter password: password
Login successful!
