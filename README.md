
# Doctor Booking App

## Overview

The Doctor Booking App is a web application that allows users to book appointments with doctors easily. It provides a user-friendly interface for patients to find and schedule visits with healthcare professionals.

## Features

- **User Registration and Login**: Users can create accounts and log in to manage their bookings.
- **Doctor Search**: Patients can search for doctors based on specialty, location, and availability.
- **Appointment Booking**: Users can book, reschedule, or cancel appointments.
- **Admin Panel**: Administrators can manage users and doctors, and view appointment statistics.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Gokila2510/Doctor-booking-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Doctor-booking-app
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

## Running the Application

### Backend

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Start the server:
   ```bash
   npm start
   ```

### Frontend

1. Open a new terminal and navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Start the React application:
   ```bash
   npm start
   ```

## API Documentation

The API is built using REST principles. Here are some key endpoints:

- **GET /api/doctors**: Fetch all doctors.
- **POST /api/appointments**: Book a new appointment.
- **DELETE /api/appointments/:id**: Cancel an appointment.

## Contributing

Contributions are welcome! Please create a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License.

## Contact

For any inquiries, please reach out to [your_email@example.com](mailto:your_email@example.com).
