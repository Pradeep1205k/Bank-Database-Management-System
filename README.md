# Bank Database Management System

A comprehensive database management system for a bank that facilitates user, cashier, and manager interactions through secure, role-based access. This project was developed using **PHP**, **SQL**, **HTML**, and **CSS**, with a focus on streamlining operations and improving the user interface.

## Features

- **User Sessions**: Revamped database operations and functionality for users, cashiers, and managers, enabling a seamless experience.
- **Role-Based Access**: Secure login system implemented with role-based access for different user types.
  - **User**: Basic banking operations.
  - **Cashier**: Transaction handling.
  - **Manager**: Access to reports, user management, and approval of operations.
- **Frontend Enhancements**: Improved the interface to ensure a more intuitive and user-friendly design.
  
## Technologies Used

- **Backend**: PHP, SQL
- **Frontend**: HTML, CSS
- **Database**: MySQL

## Project Structure

```bash
├── index.html             # Main landing page
├── login.php              # Login system for users, cashiers, and managers
├── user_dashboard.php     # Dashboard for bank users
├── cashier_dashboard.php  # Cashier session functionalities
├── manager_dashboard.php  # Manager session functionalities
├── assets/                # Stylesheets, images, and other static assets
│   └── styles.css         # Custom CSS for the frontend
├── db/                    # Database scripts and SQL files
│   └── db_connection.php  # Database connection and configuration
├── README.md              # Project documentation
```

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Bank-Database-Management-System.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Bank-Database-Management-System
   ```

3. Set up the database:
   - Import the SQL scripts located in the `db/` directory into your MySQL server.

4. Update `db_connection.php` with your database credentials.

5. Start the server and access the project via your browser.

## How to Use

- **Login**: Use the login page to sign in with appropriate credentials (user, cashier, or manager).
- **User Session**: View account details, perform transactions, etc.
- **Cashier Session**: Manage deposits, withdrawals, and other transactions.
- **Manager Session**: Manage users, view transaction reports, and approve requests.

## Future Improvements

- Integration of additional security measures (e.g., two-factor authentication).
- Enhanced reporting tools for managers.
- Further improvements in the user interface.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
