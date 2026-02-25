🛒 E-Commerce Web Application

A full-stack E-Commerce web application built using Spring Boot for the backend and React + Vite for the frontend.
This project demonstrates complete CRUD operations, REST API integration, and a responsive UI for managing products and cart functionality.

🚀 Tech Stack
🔹 Backend

Java

Spring Boot

Spring Web (REST APIs)

Spring Data JPA

H2 Database

Maven

🔹 Frontend

React

Vite

Axios

CSS

✨ Features
🛍️ Product Management (Admin Functionalities)

✅ Create new product (with image upload)

✅ Update existing product

✅ Delete product

✅ View all products

✅ Category-based filtering

✅ Stock availability handling

🛒 User Functionalities

✅ View product details

✅ Add product to cart

✅ Increase/Decrease quantity

✅ Remove item from cart

✅ Dynamic cart updates

✅ Responsive UI

🧠 Backend Architecture

The backend follows a clean layered architecture:

Controller → Service → Repository → Database

REST APIs for product operations

JPA for database interaction

H2 in-memory database for development

Proper exception handling

Image handling for product uploads

📂 Project Structure
Backend (Spring Boot)
src/main/java/com/example/ecom_proj
│
├── controller
├── service
├── repository
├── model
└── config
Frontend (React + Vite)
src/
│
├── components
├── pages
├── services
└── App.jsx
⚙️ How to Run the Project
🔹 Backend Setup

Clone the repository

git clone <your-repo-link>

Navigate to backend folder

cd backend

Run the application

mvn spring-boot:run

H2 Console:

http://localhost:8080/h2-console

Default DB settings:

JDBC URL: jdbc:h2:mem:testdb

Username: sa

Password: (leave empty)

🔹 Frontend Setup

Navigate to frontend folder

cd frontend

Install dependencies

npm install

Start development server

npm run dev

Open in browser:

http://localhost:5173
📸 Screenshots

(Add your UI screenshots here)

🎯 Learning Outcomes

Hands-on experience with Spring Boot REST APIs

CRUD operations with JPA

Frontend–Backend integration

State management in React

File upload handling

Building real-world full-stack application

📌 Future Improvements

Add Authentication & Authorization (Spring Security + JWT)

Integrate MySQL/PostgreSQL for production

Implement Payment Gateway

Deploy on cloud (AWS / Render / Railway)

👨‍💻 Author

Daksh Sanodiya
Full Stack Developer | Java & React Enthusiast

