# Employee Attendance System (EAS)
The Employee Attendance System (EAS) is a web-based application designed to streamline the management of employee attendance in organizations. This system allows administrators to efficiently track employee check-ins and check-outs, manage employee records, and generate attendance reports. Built using Node.js, Express, and MongoDB, EAS provides a user-friendly interface for both administrators and employees.

Key Features
Admin Dashboard: A comprehensive dashboard for administrators to manage employee records, view attendance data, and add new employees.

Employee Management: Easily add, update, and delete employee information, including username, phone number, and email.

Check-In and Check-Out: Employees can check in and out using their location data, which is captured via geolocation. The system ensures that employees cannot check in multiple times for the same day.

Attendance Tracking: The application records the latitude and longitude of check-ins and check-outs, along with timestamps and city information.

User Authentication: Secure login for administrators using Passport.js for authentication, ensuring that only authorized personnel can access sensitive data.

Responsive Design: The application is designed to be mobile-friendly, allowing employees to check in and out from their smartphones.

Technologies Used

Backend: Node.js, Express.js

Database: MongoDB

Authentication: Passport.js

Frontend: EJS (Embedded JavaScript), HTML, CSS

Geolocation: Utilizes browser geolocation API for capturing employee locations.
