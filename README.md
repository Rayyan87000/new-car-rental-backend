🚗 Car Rental System — Full Stack Project
<!-- HEADER CARD --> <div style="padding:20px; border-radius:12px; background:linear-gradient(135deg,#4b79a1,#283e51); color:white; box-shadow:0 4px 12px rgba(0,0,0,0.2);"> <h2>🚘 A Full Stack Car Rental Platform Built with Spring Boot + React.js</h2>

A complete system where users can browse cars, book rentals, upload licenses, and manage profiles — while admins manage companies, variants, bookings & customers.

</div>
⭐ Features
<!-- FEATURE GRID --> <div style="display:flex; gap:16px; flex-wrap:wrap;"> <div style="flex:1; min-width:280px; background:#f7f7f7; padding:16px; border-radius:12px; box-shadow:0 2px 8px rgba(0,0,0,0.1);"> <h3>👤 User Features</h3> <ul> <li>Register & Login</li> <li>Browse Cars</li> <li>View Car Details</li> <li>Book Cars</li> <li>Upload License</li> <li>Booking History</li> <li>Update Profile</li> </ul> </div> <div style="flex:1; min-width:280px; background:#f7f7f7; padding:16px; border-radius:12px; box-shadow:0 2px 8px rgba(0,0,0,0.1);"> <h3>🛠 Admin Features</h3> <ul> <li>Add Car Companies</li> <li>Add Variants</li> <li>Update/Delete Variants</li> <li>View Customers</li> <li>View All Bookings</li> <li>Manage Prices</li> </ul> </div> </div>
🖼 UI Screenshots

👇 Each image has a short explanation so interviewer instantly understands.

<!-- IMAGE CARD --> <div style="background:#ffffff; padding:16px; border-radius:12px; box-shadow:0 2px 8px rgba(0,0,0,0.1);">
🏠 Home Page

Users can browse available cars and check rent price, fuel type, seats, model year, etc.
<img src="images/Screenshot 2025-11-25 065258.png" style="border-radius:10px; width:100%;">

🔐 Login Page

Simple login for both User & Admin.
<img src="images/Screenshot 2025-11-25 065341.png" style="border-radius:10px; width:100%;">

📝 Register Page

New user can create an account with required details.
<img src="images/Screenshot 2025-11-25 065354.png" style="border-radius:10px; width:100%;">

📄 Booking Summary

Shows selected car, booking price, user information, and license upload option.
<img src="images/Screenshot 2025-11-25 065413.png" style="border-radius:10px; width:100%;">

👤 User Profile

User can view profile details & uploaded driving license.
<img src="images/Screenshot 2025-11-25 065430.png" style="border-radius:10px; width:100%;">

🧑‍💼 Admin Home

Admin dashboard showing quick navigation options.
<img src="images/Screenshot 2025-11-25 065449.png" style="border-radius:10px; width:100%;">

👥 All Customers (Admin)

Admin can view all registered customers & their license details.
<img src="images/Screenshot 2025-11-25 065503.png" style="border-radius:10px; width:100%;">

📚 All Bookings (Admin)

Admin can see complete booking history of all users.
<img src="images/Screenshot 2025-11-25 065532.png" style="border-radius:10px; width:100%;">

➕ Add Variant (Admin)

Admin adds car variant with model, rent, mileage, fuel type, seats, and image.
<img src="images/Screenshot 2025-11-25 065545.png" style="border-radius:10px; width:100%;">

</div>
🏗 Tech Stack
<!-- TECH STACK BADGES --> <div style="background:#f8f9fa; padding:20px; border-radius:12px; box-shadow:0 2px 10px rgba(0,0,0,0.08);">
🎨 Frontend
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"> <img src="https://img.shields.io/badge/Bootstrap%205-purple?style=for-the-badge&logo=bootstrap&logoColor=white">
⚙ Backend
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/MySQL-446?style=for-the-badge&logo=mysql&logoColor=white">
🧰 Tools
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"> <img src="https://img.shields.io/badge/GitHub-333?style=for-the-badge&logo=github&logoColor=white"> </div>
📁 Project Structure
Backend/
  controller/
  service/
  model/
  repository/
  application.properties

Frontend/
  CarComponent/
  UserComponent/
  BookingComponent/
  NavbarComponent/
  PageComponent/
  images/

▶️ How to Run
Backend
mvn spring-boot:run

Frontend
npm install
npm start
