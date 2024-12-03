# Invoice Project

## Overview

The Invoice Project is a web-based application designed to manage and generate invoices efficiently. It provides features for creating, editing, and tracking invoices, as well as managing client information and payment statuses.

## Features

- Create and manage invoices
- Track payment statuses
- Manage client information
- Generate PDF invoices
- User authentication and authorization

## Technologies Used

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT
- PDF Generation: pdfkit

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

3. **Install the dependencies:**

   ```bash
   npm install
   ```

4. **Set up environment variables:**

   Create a `.env` file in the root directory and add the following:

   ```plaintext
   PORT=3000
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```

5. **Start the application:**

   ```bash
   npm start
   ```

6. **Access the application:**

   Open your browser and go to `http://localhost:3000`.

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
