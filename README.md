# Loan-Management-System

# Loan Management System

Loan Management System is a web application built using Flask, a Python web framework. This application allows users to register, request loans, and manage their roles as borrowers, lenders, or administrators. It provides a simple dashboard for each user type and facilitates loan transactions.

## Features

1. User Registration:
   - Users can register using their email addresses.

2. Role Selection:
   - Users can choose roles: admin, borrower, or lender.

3. Borrower Functionality:
   - Borrowers can request loans.
   - Borrowers can view their past loans.

4. Lender Functionality:
   - Lenders can confirm and pay loans.
   - Lenders can view past loan payments.

5. Role-Based Dashboards:
   - Each user type has a customized dashboard.
   - Admins see complete transaction details.

## Project Structure

The project is structured as follows:

- `app.py`: Main Flask application file.
- `models.py`: Defines database models.
- `templates/`: Contains HTML templates.
- `static/`: Holds static files like CSS.

## Getting Started

1. Install Dependencies:
   ```bash
   pip install -r requirements.txt

Make sure to customize it according to your project's specific details and requirements.
