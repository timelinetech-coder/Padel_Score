🏓 PADELSCORE — Own Your Score

PADELSCORE is a web application for managing padel tournaments, with dedicated interfaces for admins, referees, and the public.
It provides live scoring, leaderboards, player management, and tournament organization in a simple, scalable platform.

🚀 Features
👨‍💼 Admin Dashboard

Manage players, teams, referees, and tournaments

Create new tournaments and match schedules

View and manage leaderboards

🎯 Referee Interface

Secure referee login

Real-time match scoring system

Updates instantly reflected in live leaderboard

📺 Public Live View

Live tournament updates

Player profiles & statistics

Live leaderboard standings

📂 Project Structure
padelscore/
│
├── frontend/                  # Frontend UI
│   ├── admin/                 # Admin dashboard pages
│   ├── referee/               # Referee scoring & login
│   ├── live/                  # Public live views
│   ├── assets/                # Images, icons
│   ├── css/                   # Custom styles (optional)
│   ├── js/                    # Frontend scripts
│   └── index.html             # Landing page
│
├── backend/                   # API and backend logic (Node/Django planned)
│
├── database/                  # Database schema & seed files
│
├── docs/                      # Documentation
│
└── README.md                  # Project overview

⚙️ Setup Instructions
1. Clone the repo
git clone (https://github.com/timelinetech-coder/Padel_Score)
cd padelscore

2. Frontend

Open the frontend/ folder in your browser or serve with a simple HTTP server:

cd frontend
npx serve .

3. Backend (planned)

Will be built using Node.js + Express + PostgreSQL (scalable + real-time ready).

Future setup instructions will go here.

🗄️ Database Design (Planned)

Users (admins, referees)

Players

Teams

Tournaments

Matches (live scores)

Leaderboards

✅ Roadmap

 Static UI for Admin, Referee, and Live views

 Backend API (Node.js + Express + PostgreSQL)

 Authentication (JWT/Firebase Auth/Supabase)

 Real-time scoring with WebSockets

 Deployment (DigitalOcean / AWS / Vercel)

👨‍💻 Contributing

Pull requests are welcome!
Please open an issue first to discuss what you would like to change or add.
