# Login and Registration System

A C++ console program that lets users register and log in.
User details are saved in a text file.

## What it does
- Registers a new user with a username and password
- Checks that the username is not already taken
- Checks that the username (at least 3 characters) and password (at least 4) are long enough
- Saves each password as a scrambled number instead of plain text
- Logs a user in by comparing the saved details with what they type
- Shows a clear message for every success or error
- Keeps showing the menu until the user chooses Exit

## How to run
```
g++ login.cpp -o login
./login
```
A file called users.txt is created the first time someone registers.

## A note on security
The passwords are scrambled with C++'s built-in hash function. This is a learning exercise, not real-world security. Real systems use dedicated methods such as bcrypt or Argon2, with a salt.

Built as part of my CodeAlpha C++ Programming internship.
