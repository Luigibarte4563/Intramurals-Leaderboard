# 🏆 Intramurals Leaderboard

**Intramurals Leaderboard** is a full-featured web application designed to track, display, and manage team scores, match results, player statistics, and MVP awards for intramural competitions. It includes both **admin** interfaces (to add/edit teams, players, matches) and **reporting dashboards** (leaderboards, MVP boards, and printable reports).

📍 This repository contains the **Frontend Dashboard & Reporting UI** built with HTML, TailwindCSS, and Firebase for real-time data synchronization.

---

## 📦 Features

### 🧠 Real-Time Leaderboards
- Displays overall team rankings sorted by points.
- Shows detailed MVP and match performance dashboards.

### 🏟️ Admin Management Tools
- Create, update, and delete **teams** and **players**.
- Add and edit **match results** with automatic team name lookups.
- Assign MVP for matches and finalize MVPs per sport or overall.

### 📊 Data & Statistics
- Syncs data in real-time using **Firebase Firestore listeners**.
- Dynamic dashboards update automatically with backend changes.

### 🖨️ Reporting
- Printable report views for intramural summaries.
- Export options (PDF/Excel simulation UI).

### 🔐 Authentication
- Anonymous or authenticated access to admin tools using Firebase Auth.
  
---

## 🧩 Tech Stack

| Component | Technology |
|-----------|------------|
| Frontend UI | HTML5, TailwindCSS |
| Client Logic | JavaScript (ES Modules) |
| Backend / Database | Firebase Firestore |
| Authentication | Firebase Auth |
| Hosting | (Optional) GitHub Pages or Firebase Hosting |

---

## 🚀 Installation

To run this project locally:

1. **Clone the repository**

   ```bash
   git clone https://github.com/Luigibarte4563/Intramurals-Leaderboard.git
   cd Intramurals-Leaderboard
Open index.html in your browser

You can use a local server like VSCode Live Server for best results.

Configure Firebase

Make sure you have a Firebase project set up and update the config in JS files:

js
Copy code
const firebaseConfig = {
  apiKey: "",
  authDomain: "",
  projectId: "",
  storageBucket: "",
  messagingSenderId: "",
  appId: ""
};
📁 Folder Structure
sql
Copy code
Intramurals-Leaderboard/
├─ adminDashboard/
├─ index.html
├─ playersManagement.html
├─ teamsManagement.html
├─ Matches&Results.html
├─ Leaderboard.html
├─ MVP_Management.html
├─ settings.html
├─ firebase-scripts.js
├─ reportView.html
└─ README.md
Each HTML file contains associated JS logic to handle a specific part of the app.

📌 Usage
👤 Admin
Add/edit teams

Add/edit players

Record match results

Finalize MVPs

📈 Viewer
View team rankings

Browse MVP leaderboards

Review match summaries

Print reports

📋 Data Model (Firestore)
Collections:

swift
Copy code
artifacts/{appId}/public/data/
├─ teams
├─ players
├─ matches
├─ sports
├─ mvp_formulas
├─ mvp_finalized
Each document typically contains IDs and relevant fields for lookup/mapping.

✨ Contributing
Contributions are welcome! If you find bugs or want to add features:

Fork the repository

Create a new branch (feature/xyz)

Commit your changes

Submit a Pull Request

📜 License
This project is open-source and available under the MIT License.
Feel free to reuse, adapt, and build upon this project.

⭐ Support
If you find this project useful, give it a ⭐ on GitHub!
