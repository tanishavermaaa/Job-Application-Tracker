
💼 Job Application Tracker (MERN Stack)

A full-stack Job Application Tracker web application designed to help users organize and monitor their job applications efficiently. This project uses the MERN stack — MongoDB, Express.js, React.js, and Node.js — with secure JWT-based user authentication.

---

🔍 Features

* User registration and login functionality (with JWT authentication)
* Add new job applications with details (position, company, status)
* Edit or delete existing job entries
* View a list of all job applications
* Search, sort, and filter job entries by status or date
* Fully responsive user interface
* Protected routes for authenticated users only

---

🛠️ Tech Stack

Frontend:

* React.js
* React Router DOM
* Axios
* CSS

Backend:

* Node.js
* Express.js
* MongoDB (with Mongoose)
* JSON Web Tokens (JWT)
* bcrypt.js
* dotenv
* cors

---

📁 Folder Structure

The project is divided into two main parts:

* Backend: Handles user authentication, job data storage, and all API endpoints.
* Frontend: Provides the UI for users to interact with the application and communicate with the backend via API calls.

job-application-tracker/
├── backend/
│ ├── controllers/
│ │ └── authController.js
│ │ └── jobController.js
│ ├── middleware/
│ │ └── authMiddleware.js
│ ├── models/
│ │ └── User.js
│ │ └── Job.js
│ ├── routes/
│ │ └── authRoutes.js
│ │ └── jobRoutes.js
│ ├── .env
│ ├── server.js
│
├── frontend/
│ ├── public/
│ ├── src/
│ │ ├── pages/
│ │ │ └── Login.js
│ │ │ └── Register.js
│ │ │ └── Dashboard.js
│ │ │ └── AddJob.js
│ │ │ └── EditJob.js
│ │ ├── components/
│ │ │ └── JobCard.js
│ │ ├── App.js
│ │ ├── index.js
│ ├── package.json
│
├── README.md

---

🎯 Installation and Setup

### Prerequisites:

* Node.js and npm installed
* MongoDB Atlas or local MongoDB server
* Code editor (VS Code)

### Backend Setup:

1. Navigate to the backend folder.
2. Install dependencies using npm.
3. Create a `.env` file with your MongoDB URI, JWT secret, and port.
4. Start the server.

### Frontend Setup:

1. Navigate to the frontend folder.
2. Install dependencies using npm.
3. Start the React development server.

---

🌍 Deployment

The app is deployed using Render : https://job-frontend-vercel.onrender.com


