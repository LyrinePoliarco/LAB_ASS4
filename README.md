
---

## User Login System

### Problem Statement:

Create a simple user login system that allows users to log in with a predefined password. The system should limit the number of login attempts per user and handle invalid password entries.

### Requirements:

1. Implement a user login system that prompts users to enter a password.
2. Users are allowed a maximum of 3 login attempts.
3. If a user enters an incorrect password, they should be notified and prompted to try again.
4. If a user exceeds the maximum number of login attempts, the system should block further login attempts and notify the user.
5. The valid password for login is "password".
6. Use user-defined exceptions to handle both maximum login attempts and invalid password scenarios.
7. Use a `while(true)` loop to continuously prompt the user for a password until a correct one is provided or the maximum login attempts are exceeded.

### Implementation:

- The Java code provided in `UserLogin.java` demonstrates a solution to the problem statement.
- Two user-defined exceptions, `MaxLoginAttemptsExceededException` and `InvalidPasswordException`, are created to handle maximum login attempts and invalid password scenarios, respectively.
- The program utilizes a `while(true)` loop to continuously prompt the user for a password until a correct one is provided or the maximum login attempts are exceeded.

### Instructions:

1. Compile and run the `UserLogin.java` file.
2. Follow the prompts to enter the password.
3. If the entered password is incorrect, you'll be notified and prompted to try again.
4. If the maximum number of login attempts is exceeded, further login attempts will be blocked, and you'll be notified.
5. If the correct password is entered, you'll receive a "Login successful!" message.

--- 

