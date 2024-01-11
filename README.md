# FilmBooking Project

FilmBooking is a project dedicated to providing a seamless and user-friendly platform for accessing real-time information about movie screenings and bookings. The backend is powered by a robust Spring Boot framework, ensuring reliability and efficiency in handling data.

## Overview

The FilmBooking project aims to revolutionize the way users engage with movie information. The platform focuses on presenting movie-related data through intuitive interfaces, allowing users to easily navigate and find real-time information on movie screenings and audience preferences.

## Features

- **Real-time Information:** Get up-to-date details on movie screenings and audience preferences.
- **User-friendly Interface:** Intuitive design for easy navigation and exploration of box office trends.
- **Confirmation Emails:** Receive timely updates on booked movie screenings via confirmation emails.

## Technologies Used

### Frontend
- HTML
- CSS
- JavaScript
- JSON

### Backend - Spring Boot
Spring Boot is a framework for building Java-based, production-grade applications. In our project, it serves as the backend to handle data retrieval, processing, and serving to the frontend.

### Database - MySQL
The backend seamlessly integrates with a MySQL database, efficiently storing information about movie screenings and user preferences (email, password, and username) for a reliable and organized data management system.

## Getting Started

To get started with the FilmBooking project, follow the steps below:

### Prerequisites
- Java Development Kit (JDK)
- MySQL Database
- Node.js (for frontend development)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/FilmBooking.git
   cd FilmBooking
   ```

2. Set up the frontend:
   ```bash
   # Navigate to the frontend directory
   cd frontend
   
   # Install dependencies
   npm install
   ```

3. Set up the backend:
   ```bash
   # Navigate to the backend directory
   cd backend
   
   # Build the project
   ./gradlew build
   ```

4. Configure the database:
   - Create a MySQL database and update the `application.properties` file in the `backend` directory with the appropriate credentials.

5. Run the application:
   ```bash
   # Start the backend server
   cd backend
   ./gradlew bootRun
   ```

   ```bash
   # Start the frontend server
   cd frontend
   npm start
   ```

Visit `http://localhost:3000` in your browser to access the FilmBooking platform.

## Conclusion

The FilmBooking project utilizes a MySQL database to seamlessly manage movie screenings and user data, providing a reliable platform for users to access real-time information and enhance their movie-watching experience.

Feel free to contribute and make this project even better!
