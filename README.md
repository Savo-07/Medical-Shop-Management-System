# Medical Shop Management System

## Introduction

The Medical Shop Management System is designed to automate and streamline the daily operations of a medical shop. By managing inventory, sales, customer data, and user roles, this application aims to reduce manual workloads, improve accuracy, and enhance productivity.

---

## Features

The system offers the following functionalities:

- **Inventory Management**: Add, view, update, and delete medicine stock.
- **Sales Management**: Handle transactions with detailed reporting.
- **Customer Management**: Record and update customer details efficiently.
- **User Management**: Ensure role-based access and secure login features.

---

## Technologies Used

- **Programming Language**: Python
- **Framework**: Django
- **Database**: SQLite3
- **Version Control**: Git
- **Testing Tools**: Manual and White Box Testing

---

## Installation

1. Navigate to the project directory:

   ```bash
   cd mediapplication

   ```

2. Create a virtual environment and activate it:
   `python3 -m venv venv`
   `source venv/bin/activate`

   # On Windows, use
   `venv\\Scripts\\activate`

4. Install dependencies:
   `pip install -r requirements.txt`

5. Run migrations:
   `python manage.py migrate`

6. Start the server:
   `python manage.py runserver`
   Access the application at `http://127.0.0.1:8000.`

## Testing

## Black Box Testing

Functional and security tests were conducted to validate features like:

- Patient management
- Medicine stock updates
- Admin login security
- White Box Testing

## Unit tests were implemented for models and views:

- Medicine Module: Passed all cases with 85% coverage in views.
- Patient Module: Passed after setup fixes, achieving 89% model coverage.
- Transaction Module: Validated creation processes, though view coverage is 15%.

## Run the tests using:

    python manage.py test

## Known Issues

- Security Flaws: Account blocking after multiple failed login attempts is not implemented.
- Data Validation: Invalid expiry dates for medicines are accepted.
- Test Coverage: Some modules lack sufficient test coverage.

## Contribution

Contributions are welcome! Follow these steps:

- Fork the repository.
- Create a new branch:
  `git checkout -b feature/YourFeature`
- Commit your changes:
  `git commit -m 'Add your feature'`
- Push to the branch:
  `git push origin feature/YourFeature`
- Open a pull request.

## Authors

- Chaveen Dias (22982)
- Kavindya Wijayashantha (22989)
- Savindu Yasara (23008)
- Kanishka Madhuwantha (23025)
- Ruvini Jayakody (23029)
- Shashika Silva (23046)
