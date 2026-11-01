# Password-Security-and-Authentication-Analysis


#  Password Security & Authentication Analysis

## Project Overview
Password Security & Authentication Analysis is a web-based cybersecurity project developed using Python and Flask.

The project focuses on protecting user accounts through secure password storage, password strength checking, login authentication, temporary account lockout, and authentication activity monitoring.

##  Objectives
- Implement secure user registration and login.
- Protect passwords using hashing techniques.
- Evaluate password strength.
- Prevent repeated unauthorized login attempts.
- Maintain authentication activity records.

##  Technologies Used
- Python
- Flask
- SQLite Database
- HTML
- Werkzeug Security
- Visual Studio Code

##  Key Features

**1. User Registration:** Allows users to create an account.

**2. Password Hashing:** Stores passwords in hashed form instead of plain text.

**3. User Login and Logout:** Provides secure authentication functionality.

**4. Password Strength Checker:** Checks password length, uppercase letters, lowercase letters, numbers, and special characters.

**5. Account Lockout:** Temporarily locks an account for 60 seconds after five failed login attempts.

**6. Authentication Activity Logging:** Records successful logins, failed attempts, account lockouts, and logout activities.

##  Project Structure

```text
Password_Security_Project/
│
├── app.py
├── templates/
│   ├── register.html
│   ├── login.html
│   └── password_strength.html
│
├── static/
├── README.md
└── .gitignore
```

## ⚙️ Installation and Execution

**Step 1:** Install Python.

**Step 2:** Install required packages.

```bash
pip install Flask Werkzeug
```

**Step 3:** Run the application.

```bash
python app.py
```

**Step 4:** Open the following address in your browser.

```text
http://127.0.0.1:5000
```

##  Learning Outcomes
- Practical understanding of password security.
- Knowledge of Flask web development.
- Understanding of password hashing.
- SQLite database management.
- Implementation of basic authentication security.
- Understanding of account protection mechanisms.

##  Future Improvements
- Add an administrator dashboard for viewing activity logs.
- Improve password strength analysis.
- Add email-based authentication.
- Implement additional security controls.
- Improve website design and user experience.

##  Conclusion
This project demonstrates fundamental password security and authentication techniques. It provides practical experience in Python programming, Flask development, database management, and cybersecurity concepts.
