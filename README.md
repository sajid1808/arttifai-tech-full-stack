
# 🏋️‍♂️ Full Stack Fitness Tracker App

## Features
- User registration & login (JWT-based)
- Add and log workouts (type, duration, calories)
- View personalized workout input UI
- PostgreSQL database for persistence

## Tech Stack
- **Frontend**: React.js
- **Backend**: Express.js + Node.js
- **Database**: PostgreSQL
- **Authentication**: JWT

## Setup
1. Clone the repo and run:
   ```
   cd server && npm install && node index.js
   cd ../client && npm install && npm start
   ```
2. PostgreSQL:
   - Create DB `fitness_tracker`
   - Run `database.sql` script to create tables

## Coming Soon
- Workout chart visualization
- Goal setting & progress dashboard
- Deployment to Netlify & Render
