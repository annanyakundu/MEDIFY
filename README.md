# Medify - Online Doctor Appointment Booking System

Medify is an Online Doctor Appointment Booking System that provides a streamlined solution for managing doctor appointments and communication between patients and healthcare providers.
The system features two distinct frontends: one for patients and one for administrators.

## Features

### Patient Features:
- Book appointments by filling out a simple form.
- Send messages to the admin for inquiries or updates.

### Admin Features:
- View and manage patient appointments.
- Update appointment statuses as pending, rejected, or accepted.
- View messages from patients.
- Add new doctors to the system.
- Add new admins who can access the admin dashboard.

## Deployed Frontends

- **User Website (Patient Portal):** [Medify User Website](https://medify-annanya.netlify.app/)
- **Admin Dashboard:** [Medify Admin Dashboard](https://medify-annanya-admin.netlify.app/)

## Technologies Used

- **Frontend:** React.js, Vite
- **Backend:** Node.js, Express.js, MongoDB
- **Authentication:** JWT Tokens
- **Deployment:** Render.com (Backend), Netlify (Frontend)

## Getting Started

### Prerequisites
- Node.js and npm installed on your machine.
- MongoDB for database management.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/medify.git
   ```

2. Navigate to the backend directory and install the required dependencies:
   ```bash
   cd backend
   npm install
   ```

3. Navigate to the frontend directory and install the required dependencies:
   ```bash
   cd frontend
   npm install
   ```

### Running the Application

1. Start the MongoDB server on your local machine.

2. Start the backend server:
   ```bash
   cd backend
   npm start
   ```

3. Start the frontend development server:
   ```bash
   cd frontend
   npm run dev
   ```

4. Access the application at `http://localhost:3000` for the frontend and `http://localhost:5000` for the backend.

## Deployment

- The backend is deployed on Render.com.
- The frontend for both the patient portal and admin dashboard is deployed on Netlify.

## Contributing

If you'd like to contribute to Medify, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License

This project is open-source and available under the MIT License.
