UniEv 🎓
Evinde Üniversite Hayatı

A modern student housing & roommate matching platform designed to simplify university life by helping students find accommodation, roommates, and communicate safely in one integrated system.

📌 About The Project

UniEv is a full-stack university housing platform developed to help students:

Find trusted rental listings
Match with compatible roommates
Chat in real-time
Manage favorites and profiles
Access safety and fraud prevention tools

The platform also includes an advanced admin panel for monitoring users, reports, listings, and platform activity.

🚀 Main Features
🔐 Authentication & Authorization
🏠 Property Listings System
❤️ Favorites System
💬 Real-Time Messaging (Socket.IO)
🤝 Roommate Match Engine
🛡️ Fraud Detection & Safety Map
👤 Profile Management
📸 Image Upload Support
📊 Admin Dashboard
📧 Email Verification System
🔔 Notifications System
📱 Responsive UI
🛠️ Technologies Used
Backend
Python 3.12+
FastAPI
SQLAlchemy
SQLite / PostgreSQL
Socket.IO
JWT Authentication
Frontend
HTML5
CSS3
JavaScript
Tools
Uvicorn
Git & GitHub
VS Code
📂 Project Structure
UniEv/
│
├── core/
├── templates/
├── static/
├── uploads/
├── database.py
├── main.py
├── create_admin.py
├── create_test_data.py
├── requirements.txt
├── .env.example
└── HOW_TO_RUN.md
⚙️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/Hashem404/UniEv.git
cd UniEv
2️⃣ Create Virtual Environment
python -m venv venv

Activate it:

venv\Scripts\activate
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Configure Environment Variables
copy .env.example .env

Then edit .env file.

5️⃣ Run The Server
python -m uvicorn main:app --reload
🌐 Access The Application
Service	URL
Main Website	http://localhost:8000
Swagger Docs	http://localhost:8000/docs
ReDoc Docs	http://localhost:8000/redoc
👨‍💼 Create Admin Account
python create_admin.py
🧪 Create Test Data
python create_test_data.py
📸 Screenshots

Add your screenshots here

![Home](screenshots/home.png)
![Dashboard](screenshots/dashboard.png)
![Listings](screenshots/listings.png)
📖 Full Setup Guide

A complete beginner-friendly setup guide is available here:

HOW_TO_RUN.md
🎥 Demo Video

Add your presentation / lansman video link here.

Example:

[Watch Demo Video](https://youtube.com/your-video)
👥 Team
ŞARJÖR Team
Hashem Salem
🔒 Security Features
Password Hashing
JWT Authentication
Fraud Score Detection
Login Protection
Role-Based Access Control
Email Verification
📈 Future Improvements
Mobile Application
AI Roommate Recommendation
Payment Integration
Google Maps Integration
Multi-Language Support
📄 License

This project was developed for academic and educational purposes.

⭐ Support

If you like this project, consider giving it a ⭐ on GitHub:
