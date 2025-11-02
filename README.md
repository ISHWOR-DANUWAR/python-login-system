# python-login-system
A beginner-friendly Python login program that demostrates authentication logic, loops and conditional statements with attempt limiting.

## Description

This program simulates a basic user authentication system where users must provide their name, ID, and password to access their profile information. It includes security features like attempt limiting to prevent brute force attacks. 

## Features

- **User Authentication**: Validates username, user ID, and password
- **Attempt Limiting**: Maximum 3 failed login attempts before lockout
- **Exit Option**: Users can type 'exit' to quit the program anytime
- **Profile Display**: Shows detailed user information upon successful login
- **Input Validation**: Checks all three credentials before granting access

## How It Works

1. User is prompted to enter their name, ID and password
2. Program Validates credentials against stored user data
3. On success: Displays user profile and exits
4. On failure: Shows remaining attempts and allows retry
5. After 3 failed attempts: Access is denied and program terminates

## Pre-configured Users

| Username | User ID | Password | Profile |
|----------|---------|----------|---------|
| GRA-1    | 001     | gra_01   | Software Developer at Google |
| MAYA-1   | 011     | maya@03  | AI Engineer at Meta |

## Usage 
```bash
python login_system.py
```

## Example session 
```
Hello User 2.0, Enter your info to check out your data.
Enter your name (or type 'exit' to quit): GRA-1
Enter your ID: 001
Enter your password: gra_01
Welcome GRA-1, Check out your details.
{'Name': 'Hanry', 'Age': '25', 'Nationality': 'American', 
 'Profession': 'Software Developer', 'Workplace': 'Google', 
 'Salary': '$150,000'}
```

## Concepts Demostrated

- `while` loops for repeated operations
- Conditional statements (`f`, `elif`, `else`)
- String comparison and validation
- Dictionary data structures
- User input handling
- Break statements for loops control

## Future Improvements
- [ ] Add password hashing for security
- [ ] Store user data in external file/database
- [ ] Implement user registration feature
- [ ] Add password reset functionality
- [ ] Create GUI interface

## Technologies Used

- Python 3.x

## Author

Ishwar Danuwar
