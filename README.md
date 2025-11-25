🚗 Car Rental System — Full Stack Project

A full-stack Car Rental System developed using Spring Boot (backend) and React.js (frontend) with MySQL as the database.
The project allows users to browse cars, book rentals, upload license, and manage profiles, while admins can manage companies, variants, bookings, and customers.

⭐ Features
👤 User Features

Register & Login

Browse available cars

View car details

Book a car for selected dates

Upload a driving license

View booking history

Update profile

🛠️ Admin Features

Add car companies

Add car variants

Update/delete variants

View all customers

View all bookings

Manage rental prices

🖼️ UI Screenshots

(Add images later by replacing the placeholder text)

Home Page
(Insert image here)

User Login Page
(Insert image here)

User Registration Page
(Insert image here)

Booking Summary Page
(Insert image here)

User Profile Page
(Insert image here)

Admin Home / Dashboard
(Insert image here)

All Customers (Admin)
(Insert image here)

All Bookings (Admin)
(Insert image here)

Add Variant (Admin)
(Insert image here)

🏗 Tech Stack
Frontend

React.js

Axios

Bootstrap 5

React Router

Backend

Spring Boot

Spring MVC

Spring Data JPA

Hibernate

MySQL

Tools

Spring Tool Suite (STS)

VS Code

MySQL Workbench

Git & GitHub

📁 Project Structure
Backend
src/main/java/com/carrentalsystem/
  controller/
  service/
  repository/
  model/
src/main/resources/
  application.properties

Frontend
src/
  BookingComponent/
  CarComponent/
  UserComponent/
  NavbarComponent/
  PageComponent/
  images/

🧩 API Endpoints (Short)
Auth

POST /api/auth/login

POST /api/auth/register

User

GET /api/user/variants

POST /api/user/booking/add

Admin

POST /api/admin/company/add

POST /api/admin/variant/add

GET /api/admin/customer/all

GET /api/admin/bookings/all

▶️ How to Run the Project
Backend (Spring Boot)

Create MySQL database:

car_rental_system


Update application.properties with your username + password

Run via:

mvn spring-boot:run


Backend runs on:

http://localhost:8080

Frontend (React)
npm install
npm start


Runs on:

http://localhost:3000
