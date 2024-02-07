# Custom Mailing Application

This is a simple custom mailing application built with React.js for the frontend and Node.js for the backend.

## Description

This application allows users to send emails to specified recipients with a subject and message. It provides a user-friendly interface for composing and sending emails.

## Features

- Compose emails with a recipient's email address, subject, and message.
- Send emails securely using SMTP.
- Receive notifications for successful email sending.

## Installation

### Prerequisites

- Node.js installed on your machine.
- NPM (Node Package Manager) installed on your machine.
- SMTP server credentials for sending emails.

### Steps

1. Clone the repository:

git clone <repository_url>


2. Navigate to the project directory:

cd custom-mailing-app

3. Install dependencies for both frontend and backend:

cd frontend
npm install
cd ../backend
npm install

4. Set up environment variables:

   - Create a `.env` file in the `backend` directory.
   - Add the following variables:


PORT=<port_number>
SMTP_HOST=<smtp_host>
SMTP_PORT=<smtp_port>
SMTP_MAIL=<smtp_email>
SMTP_PASSWORD=<smtp_password>

5. Start the backend server:

cd backend
npm start

6. Start the frontend development server:

cd ../frontend
npm start

7. Open your browser and navigate to `http://localhost:3000` to use the application.

## Usage

1. Fill in the recipient's email address, subject, and message in the provided form fields.
2. Click on the "Send Email" button to send the email.
3. Receive a notification upon successful email sending.

## Technologies Used

- React.js
- Node.js
- Express.js
- Nodemailer
- Chakra UI

## Contributors

- [Amardeep](https://github.com/Amardeep23)



