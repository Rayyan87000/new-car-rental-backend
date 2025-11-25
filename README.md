🚗 Car Rental System — Full Stack Project
<!-- HEADER CARD --> <div style="padding:20px; border-radius:12px; background:linear-gradient(135deg,#4b79a1,#283e51); color:white;"> <h1>🚘 Full Stack Car Rental Platform</h1> <p>A complete system built with <b>Spring Boot + React.js</b> where users can browse cars, book rentals, upload licenses, and manage profiles — while admins manage companies, variants, bookings & customers.</p> </div>
⭐ Features
<div style="display:flex; gap:16px; flex-wrap:wrap;"> <div style="flex:1; min-width:300px; background:#f7f7f7; padding:16px; border-radius:12px;"> <h3>👤 User Features</h3> <ul> <li>Register & Login</li> <li>Browse Cars</li> <li>View Car Details</li> <li>Book Cars</li> <li>Upload License</li> <li>Booking History</li> <li>Update Profile</li> </ul> </div> <div style="flex:1; min-width:300px; background:#f7f7f7; padding:16px; border-radius:12px;"> <h3>🛠 Admin Features</h3> <ul> <li>Add Car Companies</li> <li>Add Variants</li> <li>Update/Delete Variants</li> <li>View Customers</li> <li>View All Bookings</li> <li>Manage Prices</li> </ul> </div> </div>
🖼 UI Screenshots

(Clean layout + Smaller Image Sizes)

🏠 <h2>Home Page</h2>
<img src="images/Screenshot 2025-11-25 065258.png" width="75%" style="border-radius:10px;">
🔐 <h2>Login Page</h2>
<img src="images/Screenshot 2025-11-25 065341.png" width="75%" style="border-radius:10px;">
📝 <h2>Register Page</h2>
<img src="images/Screenshot 2025-11-25 065354.png" width="75%" style="border-radius:10px;">
📄 <h2>Booking Summary</h2>
<img src="images/Screenshot 2025-11-25 065413.png" width="75%" style="border-radius:10px;">
👤 <h2>User Profile</h2>
<img src="images/Screenshot 2025-11-25 065430.png" width="75%" style="border-radius:10px;">
🧑‍💼 <h2>Admin Home</h2>
<img src="images/Screenshot 2025-11-25 065449.png" width="75%" style="border-radius:10px;">
👥 <h2>All Customers (Admin)</h2>
<img src="images/Screenshot 2025-11-25 065503.png" width="75%" style="border-radius:10px;">
📚 <h2>All Bookings (Admin)</h2>
<img src="images/Screenshot 2025-11-25 065532.png" width="75%" style="border-radius:10px;">
➕ <h2>Add Variant (Admin)</h2>
<img src="images/Screenshot 2025-11-25 065545.png" width="75%" style="border-radius:10px;">
🏗 Tech Stack
<div style="background:#ffffff; padding:20px; border-radius:12px;"> <h3>🎨 Frontend</h3> <p> <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"> <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"> </p> <h3>⚙ Backend</h3> <p> <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white"> </p> <h3>🧰 Tools</h3> <p> <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"> <img src="https://img.shields.io/badge/STS%204-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"> </p> </div>
📁 Project Structure
<!-- STRUCTURE CARD --> <div style="background:#f7f7f7; padding:20px; border-radius:12px; box-shadow:0 2px 10px rgba(0,0,0,0.08);"> <h3>📦 Backend Structure</h3>
Backend/
 ├── controller/
 ├── service/
 ├── repository/
 ├── model/
 └── resources/
      └── application.properties

<h3>🎨 Frontend Structure</h3>
Frontend/
 ├── CarComponent/
 ├── UserComponent/
 ├── BookingComponent/
 ├── NavbarComponent/
 ├── PageComponent/
 └── images/

</div>
▶️ How to Run the Project (Styled Version)
<!-- RUN CARD --> <div style="background:#ffffff; padding:20px; border-radius:12px; box-shadow:0 2px 10px rgba(0,0,0,0.08);"> <h2>⚙️ Step-by-Step Setup Guide</h2>
✅ 1. Clone Repositories
git clone https://github.com/YourUsername/new-car-rental-backend.git
git clone https://github.com/YourUsername/new-car-rental-frontend.git

✅ 2. Setup MySQL Database
<div style="padding-left:10px;"> • Install MySQL & MySQL Workbench • Create the database: </div>
CREATE DATABASE car_rental_system;

<div style="padding-left:10px;"> • Update backend configuration in: <b>src/main/resources/application.properties</b> </div>
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD

✅ 3. Run Backend (Spring Boot)
mvn spring-boot:run


🔗 Backend will run at:
http://localhost:8080

✅ 4. Run Frontend (React)
npm install
npm start


🔗 Frontend will run at:
http://localhost:3000

</div>
