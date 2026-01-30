🍽️ FoodShare – Food Waste Management System

FoodShare is a Single Page Web Application (SPA) designed to reduce food waste by connecting food donors (hotels, individuals, organizations) with NGOs that can redistribute surplus food efficiently. The platform enables quick posting, discovery, and claiming of food donations using a simple, location-based system.

🚀 Features

🔐 Role-based Authentication (Admin, Donor, NGO)

🏠 Donor Dashboard to post food donations (quantity, expiry, location)

🗺️ Location-based matching using interactive maps

📍 Leaflet.js Map Integration

📏 Distance calculation using Haversine Formula

📊 NGO Dashboard to find and claim nearby food

🛠️ Admin Panel for user and complaint management

📝 Complaint, Feedback & Rating System

⚡ Single Page Application architecture

💾 Client-side storage using LocalStorage & SessionStorage

🧑‍💻 Technology Stack

Frontend

HTML

Tailwind CSS

JavaScript

Maps & UI

Leaflet.js

Font Awesome

Storage

LocalStorage

SessionStorage

Architecture

Single Page Application (SPA)

Future Scope

Node.js

MongoDB (MERN Stack)

🏗️ System Roles
Role	Description
Admin	Monitors system, manages users, resolves complaints
Donor	Posts food donations and confirms pickup
NGO	Finds nearby food, claims donations, tracks status
🔄 Workflow

Donor posts surplus food with quantity, expiry and location.

NGO searches nearby donations using map view.

NGO sends request for pickup.

Donor confirms request.

Status updates automatically.

🛠️ Step-by-Step Run Guide
1️⃣ Run Backend (Server)

Open terminal and run:

cd server
npm install
node index.js


If everything works correctly, you will see output like:

Server running on port 5000
Connected to DB

2️⃣ Run Frontend (Client)

Open a new terminal and run:

cd client
npm install
npm run dev


You will get output like:

Local: http://localhost:5173


Open this link in your browser.

🔑 Demo Login Credentials

Admin Login
Email: admin@food.com
Password: 123

NGO Employee Login
Email: ngo@help.com
Password: 123

Donor Employee Login
Email: donor@hotel.com
Password: 123

📌 Project Purpose

Reduce food wastage

Help needy people

Provide centralized donation platform

Enable real-time food availability

🔮 Future Enhancements

Backend integration using Node.js & MongoDB

Live GPS tracking

Push notifications

Mobile application

Employee management system
