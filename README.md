# User Registration and Login System

A Java-based user registration and login system that validates usernames and passwords, provides login feedback, and uses JUnit tests to verify the validation functionality.

## Features

### Username Validation

The system checks whether a username meets the required format.

The username validation includes:

* A maximum of 5 characters
* An underscore requirement
* Alphanumeric characters and underscores

The application displays a success or error message depending on the entered username.

### Password Validation

The password must meet complexity requirements, including:

* At least 8 characters
* At least one uppercase letter
* At least one lowercase letter
* At least one number
* At least one special character

Regular expressions are used to perform the password validation.

### Login

After registration validation, the system checks the entered username and password and displays a welcome message when authentication is successful.

The project also demonstrates both successful and unsuccessful login attempts.

### JUnit Testing

JUnit tests are included to test the username and password validation.

The tests cover:

* Correctly formatted usernames
* Incorrectly formatted usernames
* Valid passwords
* Invalid passwords

For example, the test class checks both valid and invalid username formats and password complexity.

## Technologies Used

* Java
* Java Swing
* JUnit
* Object-Oriented Programming
* Regular Expressions
* `JOptionPane`

## Application Flow

```text
Start Application
       ↓
Enter Username
       ↓
Validate Username
       ↓
Enter Password
       ↓
Validate Password
       ↓
Enter Name & Last Name
       ↓
Login
       ↓
Display Login Result
```

## Testing

The `UserLoginTest` class uses JUnit to verify that the validation methods work as expected.

Example test cases include:

```text
Username: kyl_l
Result: Valid

Username: Lilo745!!
Result: Invalid

Password: Ch&&sec@ke99!
Result: Valid

Password: kyll
Result: Invalid
```

The project demonstrates basic unit testing by using assertions such as `assertTrue` and `assertEquals`.

## Project Structure

```text
User-Registration-Login/
│
├── POEPart1.java
├── UserLogin.java
├── UserLoginTest.java
└── README.md
```

## What I Learned

This project helped me develop experience with:

* Java programming
* User input handling
* Conditional statements
* Switch statements
* Regular expressions
* Input validation
* Object-oriented programming
* JUnit unit testing
* Writing test cases
* Handling successful and unsuccessful login attempts

## Future Improvements

Possible improvements include:

* Store registered users in a database
* Add password hashing
* Add multiple user accounts
* Improve username validation
* Add account management
* Add a graphical user interface
* Add more automated tests
* Improve error handling
* Add persistent user data

## Author

Lydia Bizuhen 

This project was created as part of my Java programming coursework and is included in my software development portfolio.
