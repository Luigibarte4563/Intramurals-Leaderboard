# 🏆 Intramurals Leaderboard

![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue?style=flat-square&logo=github)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=flat-square&logo=javascript)
![Firebase](https://img.shields.io/badge/Firebase-Firestore-orange?style=flat-square&logo=firebase)

**Intramurals Leaderboard** is a web-based system designed to manage and display intramural competition data such as team standings, match results, player statistics, and MVP awards.  
It uses **Firebase Firestore** for real-time updates and supports both **Admin** and **Viewer** dashboards.

🔗 Repository:  
https://github.com/Luigibarte4563/Intramurals-Leaderboard

---

## 🌐 Live Demos

### 🔐 Admin Dashboard
Used for managing teams, players, matches, and scores.

👉 https://luigibarte4563.github.io/Intramurals-Leaderboard/

### 👀 Viewer Dashboard
Public-facing dashboard for viewing standings, match results, and statistics.

👉 https://luigibarte4563.github.io/Intramurals-Leaderboard/ViewerDashboard/home.html

---

## 🛠️ Features

### Admin Features
- Admin authentication
- Add, edit, and delete teams
- Add, edit, and delete players
- Create and manage matches
- Update scores and match status
- Assign MVPs
- Real-time Firestore updates

### Viewer Features
- View live team leaderboards
- View match results and schedules
- View player rankings and MVPs
- Sport-based filtering
- Read-only public access

---

## ⚡ Technologies Used

- **Frontend:** HTML, CSS, JavaScript (ES Modules)
- **Database:** Firebase Firestore
- **Authentication:** Firebase Auth (Anonymous Sign-In / Admin Login)
- **Hosting:** GitHub Pages

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Luigibarte4563/Intramurals-Leaderboard.git
cd Intramurals-Leaderboard
2️⃣ Run Locally
Open index.html directly in a browser or use a local server:

bash
Copy code
# Using VS Code Live Server
http://127.0.0.1:5500/index.html
3️⃣ Firebase Setup
Ensure your Firebase configuration is correctly set in the JavaScript files:

Firebase App

Firebase Auth

Firebase Firestore

Firestore security rules

🔧 Usage
Admin Dashboard

Manage teams, players, and matches

Update scores and standings

Control competition data

Viewer Dashboard

View leaderboards and match results

Monitor live updates

No login required

📂 Project Structure
bash
Copy code
Intramurals-Leaderboard/
├─ index.html                # Admin dashboard entry
├─ ViewerDashboard/
│  └─ home.html              # Viewer dashboard
├─ assets/                   # Images, CSS, JS assets
├─ scripts/                  # Firebase & application logic
└─ README.md
🤝 Contribution
Contributions are welcome!

Fork the repository

Create a new branch

Commit your changes

Open a Pull Request

UI improvements, feature additions, and optimizations are encouraged.
