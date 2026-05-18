🚀 Smart Portfolio Management System

A modern full-stack Portfolio Management Platform developed using Laravel, React.js, SQLite, Tailwind CSS, and Framer Motion.

This platform helps investors manage investments, track portfolio performance, analyze risks, calculate ROI, and monitor financial growth through a responsive and interactive dashboard.

✨ Features

🔐 Authentication System
• User Registration
• Secure Login & Logout
• Password Reset
• Email Verification
• Role-Based Access Control

📊 Dashboard Analytics
• Portfolio Overview
• ROI Analysis
• Profit/Loss Tracking
• Investment Statistics
• Interactive Charts

💼 Portfolio Management
• Add Investments
• Edit Investments
• Delete Investments
• Asset Tracking
• Investment History

📈 Financial Analytics
• Portfolio Growth Analysis
• Asset Allocation Charts
• Monthly Performance Reports
• Investment Comparison

⚠️ Risk Analysis
• Risk Score Evaluation
• Portfolio Diversification
• Smart Recommendations
• High / Medium / Low Risk Detection

🔔 Notifications System
• Investment Alerts
• Risk Notifications
• Activity Updates

🛠️ Admin Panel
• User Management
• Dashboard Monitoring
• Reports Management

🧑‍💻 Tech Stack

Frontend
• React.js
• Vite
• Tailwind CSS
• Framer Motion
• Recharts
• Axios

Backend
• Laravel 12
• Laravel Sanctum
• SQLite
• REST APIs

🎨 UI/UX Features
• Responsive Design
• Modern Dashboard
• Interactive Charts
• Smooth Animations
• Clean User Interface

📂 Project Structure

smart-portfolio-management-system/
│
├── backend/
├── frontend/
└── README.md

⚙️ Installation

1️⃣ Clone Repository

git clone https://github.com/varmaadarsh/Smart-Portfolio-Management-System.git

🔥 Backend Setup

cd backend
composer install
cp .env.example .env
php artisan key:generate

Create SQLite Database:

touch database/database.sqlite

Run Migrations:

php artisan migrate

Start Backend Server:

php artisan serve

⚡ Frontend Setup

cd frontend
npm install
npm run dev

📊 Financial Calculations

Current Value = Quantity × Current Price

Profit/Loss = (Current Price - Buy Price) × Quantity

ROI = Profit / Investment × 100

🔐 Security Features
• Password Hashing
• Sanctum Authentication
• Protected Routes
• Middleware Authorization

🚀 Future Enhancements
• AI Investment Recommendations
• Real-Time Market APIs
• Multi-Currency Support
• Advanced Analytics

👨‍💻 Author

Adarsh Varma

GitHub:
https://github.com/varmaadarsh

⭐ Support

If you like this project, give it a ⭐ on GitHub!
