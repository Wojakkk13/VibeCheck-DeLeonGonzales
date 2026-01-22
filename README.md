# VibeCheck-DeLeonGonzales

## Project Overview
A full-stack web application developed for **CPE 411L**. This project demonstrates a **Node.js and Express** backend integrated with a vanilla JavaScript frontend to perform various API operations, including fetching data and managing a server-side counter.

---

## Features

### Backend API Endpoints
* **GET /api/fortune** - Returns a random developer fortune from a pre-defined array.
* **GET /api/joke** - Returns a random programming-related joke.
* **GET /api/vibe?mood=** - Returns a specific message based on the mood query parameter (happy, tired, or stressed).
* **POST /api/smash** - Increments a global counter on the server to track smash events.
* **GET /api/smashes** - Returns the current value of the smash counter.
* **GET /api/secret?code=411L** - A protected route that reveals a hidden message when the correct code is provided.

### Frontend Features
* **Modern Dark UI** - A high-contrast design using dark backgrounds and neon text for high readability.
* **Interactive Buttons** - Custom-styled buttons with hover transitions for a responsive user experience.
* **Dynamic Content Display** - A dedicated output area that displays JSON responses from the API in real-time.

---

## Tech Stack

### Backend
* **Node.js** - JavaScript runtime environment.
* **Express** - Web framework for building the API routes.
* **CORS** - Middleware used to allow the frontend to communicate with the backend server.

### Frontend
* **HTML5/CSS3** - Structure and styling, including a custom dark theme.
* **Vanilla JavaScript** - Logic for handling button clicks and making asynchronous Fetch requests to the API.

---

## Project Structure
```text
VibeCheck-DeLeonGonzales/
├── backend/
│   ├── index.js          # Main server file containing API routes
│   └── package.json      # Project dependencies and metadata
├── frontend/
│   ├── index.html        # Main HTML structure and CSS styles
│   └── app.js            # Frontend logic and API integration
└── README.md             # Project documentation

```

## Installation and Setup

---

## 1. Backend Setup
- **Navigate** to the backend directory: `cd backend`
- **Install** the necessary packages: `npm install`
- **Start** the API server: `node index.js`
- The server will be **active** at: **http://localhost:3000**

---

## 2. Frontend Setup
- **Locate** the `frontend` folder.
- **Open** `index.html` in any modern web browser to interact with the application.

---

## Git Workflow
This project followed a structured branching strategy to satisfy collaboration requirements:

- **feature/api-routes**: Created to set up the core GET endpoints and data arrays.
- **feature/smash-counter**: Created to implement the POST request logic and server-side logging.
- **feature/frontend-ui**: Created to implement the final CSS design and user interface enhancements.

---

## Team Members
- **Adrian Paul Gonzales**
- **Rheynn De Leon**

---

**Made for CPE 411L - VibeCheck Eyyy!**

---

