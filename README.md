# Pick-Drive Car Rental Web App

The Pick-Drive Car Rental application is a robust web-based platform designed to provide users to rent cars using various devices such as computers, phones, tablets, or mobile devices. The application caters to different user roles, including unregistered users, customers, and administrators, each with specific functionalities.

## Key Features

1. **Web Application:**
   - The Car Rental Application is a web-based platform accessible through web browsers on computers, phones, tablets, and other mobile devices.

2. **Security:**
   - Security measures are implemented to safeguard user data and ensure the overall integrity of the application.

3. **Quick Response:**
   - The application ensures a rapid response to user requests, with a display time of nearby responses limited to 5 seconds.

## User Authentication and Authorization

1. **User Registration:**
   - Anonymous users can register with the application using their information.

2. **User Login:**
   - Registered users can log in to the application after registration.

3. **User Information:**
   - Authenticated users can view and update their own information.

4. **Password Management:**
   - Authenticated users can update their passwords.

5. **Admin User Operations:**
   - Admin users can retrieve, update, and delete user information.
   - Admin users can generate an Excel report of all users' information.

## Car Information

1. **Anonymous User Access:**
   - Anonymous users can retrieve information about all cars and a specific car.

2. **Admin Car Operations:**
   - Admin users can add, update, and delete cars.
   - Admin users can upload, retrieve, and display car images.
   - Admin users can update a car with a new image.

## Reservation Management

1. **User Reservations:**
   - Authenticated users can make reservations for cars.
   - Authenticated users can check the availability of a car between selected dates.

2. **Admin Reservation Operations:**
   - Admin users can add reservations for a specific car and user.
   - Admin users can retrieve, update, and delete reservations.
   - Admin users can generate Excel reports for all reservations, a specific reservation, and a user's reservations.

## How to run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/pick-drive.git
   ```
2. How to run the application:
   2a. node_modules
   ```bash
   npm install
   ```
   2b. run command
   ```bash
   npm run dev
   ```      
