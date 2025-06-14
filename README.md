-MedMate – Your Personal Medication Reminder-

-Project Objective-
MedMate is a web-based application designed to help users manage and track their medication schedule. It allows users to set medicine reminders and get notified when it’s time to take their medication.

-Tech Stack-
- Frontend: HTML, CSS, JavaScript
- Backend: Node.js (Express)
- Database: MongoDB (via Mongoose)
- Authentication: JWT-based user login system
- Scheduler: Cron jobs or setInterval for notifications
- Deployment: Can be hosted on Heroku, Vercel, or localhost

-Key Features-
- User Sign Up & Login (Authentication)
- Set medication time and frequency
- Dashboard to view active reminders
- Mark medicine as taken or missed
- Notification system for alerts

-Folder Structure-

```
/medmate
│
├── public/               # Frontend assets (HTML, CSS, JS)
├── routes/               # Express routes (auth, medicine)
├── models/               # MongoDB schemas
├── controllers/          # Business logic
├── .env                  # Environment variables
├── server.js             # Entry point for Node app
```

-How to Run Locally-
1. Clone the repo:
   ```bash
   git clone https://github.com/sreedivyanagalli/Medmate.git
   cd Medmate
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up `.env` file with:
   ```text
   MONGO_URI=your_mongo_connection
   JWT_SECRET=your_secret
   ```
4. Run the app:
   ```bash
   npm start
   ```
-Skills-
`Node.js`, `MongoDB`, `Full Stack App`, `Medication Reminder`, `REST API`, `JWT Authentication`, `HTML`, `CSS`, `JavaScript`, `Express.js`, `HealthTech`
