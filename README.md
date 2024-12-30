<h1 align="center">Internet Cafe Management System</h1>

# Overview

The Internet Cafe Management System is a Python application designed to manage the operations of an internet cafe. It uses SQLite3 for database management and offers various functionalities for managing PCs, IC cards, user sessions, and feedback. The system supports PC allocation, balance management, session history, and administrative operations.

# Features

- **PC Management**: Allocate, create, and delete PCs.
- **IC Card Management**: Apply for IC cards, check balance, and update or delete IC cards.
- **User Session Management**: Allocate PCs to users, track session history, and handle payments.
- **Feedback and History**: View feedback and session history.
- **Admin Operations**: Admin login for accessing and managing system functionalities.


# Setup

1. **Install Dependencies**: Ensure you have Python installed. The project uses the built-in SQLite3 library, so no additional dependencies are required.

2. **Run the Application**: Execute the main script to start the Internet Cafe Management System.

    ```bash
    python main.py
    ```

# Usage

1. **Admin Login**: Use the credentials (`username: system`, `password: tiger`) to access the admin functionalities.

2. **PC Operations**: Allocate PCs to users, view available PCs, create new PCs, or delete faulty PCs.

3. **IC Card Operations**: Apply for new IC cards, check balance, update balance, or delete IC cards.

4. **User Session Management**: Allocate PCs to users, track time used, and handle payments.

5. **Feedback and History**: View feedback from users and review session history.

