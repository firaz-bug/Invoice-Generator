# Invoice Project

## Overview

The Invoice Project is a Django-based web application designed to streamline the process of creating, managing, and tracking invoices. It offers features such as client management, invoice generation, and payment tracking.

## Features

- Create and manage invoices
- Track payment statuses
- Manage client information
- Generate PDF invoices
- User authentication and authorization

## Technologies Used

- Backend: Django
- Database: SQLite (default) or PostgreSQL
- Frontend: HTML, CSS, JavaScript
- PDF Generation: WeasyPrint or ReportLab
- Authentication: Django's built-in authentication system

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/invoice-project.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd invoice-project
   ```

3. **Create a virtual environment:**

   ```bash
   python -m venv venv
   ```

4. **Activate the virtual environment:**

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

5. **Install the dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

6. **Set up environment variables:**

   Create a `.env` file in the root directory and add the following:

   ```plaintext
   SECRET_KEY=your_secret_key
   DEBUG=True
   ALLOWED_HOSTS=localhost,127.0.0.1
   ```

7. **Apply migrations:**

   ```bash
   python manage.py migrate
   ```

8. **Create a superuser:**

   ```bash
   python manage.py createsuperuser
   ```

9. **Start the development server:**

   ```bash
   python manage.py runserver
   ```

10. **Access the application:**

    Open your browser and go to `http://localhost:8000`.

## Usage

1. **Register/Login:**

   - Register a new account or log in with existing credentials.

2. **Create an Invoice:**

   - Navigate to the "Create Invoice" section.
   - Fill in the client details, items, and amounts.
   - Save the invoice.

3. **Manage Invoices:**

   - View all invoices in the "Invoices" section.
   - Edit or delete invoices as needed.

4. **Generate PDF:**

   - Click on an invoice to view details.
   - Use the "Generate PDF" button to download the invoice as a PDF.
