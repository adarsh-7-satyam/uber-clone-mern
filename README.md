#  Uber Clone (MERN Stack)

This is a **full-stack Uber Clone application** that we built using the **MERN stack** — MongoDB, Express.js, React.js, and Node.js.  
Our goal was to recreate the main features of the Uber app, such as user and driver (captain) registration, login, ride requests, and map-based location tracking using the Google Maps API.

This project was created by Adarsh Satyam, Bambam Harsh Choudhary and Aditya Kumar Gautam as part of our web development project for CSP 203. We wanted to challenge ourselves with a project that combines frontend, backend, and API integration in one complete system.

---

##  Overview

Our Uber Clone supports two types of users:

- **Riders (Users):** Can sign up, log in, choose pickup and drop locations, and request rides.  
- **Captains (Drivers):** Can sign up, log in, and accept ride requests from nearby users.

The app connects everything through a Node.js + Express backend and stores data in MongoDB.  
On the frontend, we used React to create an interactive interface that connects with the Google Maps API to show real-time routes and distance calculations.

---

##  Key Features

Here’s a quick breakdown of what we implemented throughout the project:

###  1. Server Setup & User Authentication
- Set up the **Node.js + Express** server and connected it with **MongoDB**.
- Added routes for **user registration and login**.
- Used **bcrypt** for password hashing and **JWT tokens** for authentication.

###  2. User Profile & Auth Middleware
- Created authentication middleware to secure private routes.
- Implemented logout functionality and user profile management.

###  3. Captain Authentication
- Built a separate **Captain model and routes** for driver accounts.
- Implemented captain registration, login, and authentication logic.

###  4. Forms for Users & Captains
- Designed clean and responsive forms in **React** for both users and captains.
- Connected them to backend APIs using **Axios** for real-time communication.

###  5. API Integration with React
- Integrated the backend endpoints into React.
- Stored authentication tokens in local storage for persistent login sessions.

###  6. User Home Screen
- Built a modern and intuitive **User Home Page** where riders can search and book rides.
- Added map and navigation components for a realistic experience.

###  7. Location Search & Google Maps API
- Integrated the **Google Maps API** to fetch location suggestions and coordinates.
- Implemented a distance and time calculator using Google’s Distance Matrix API.

###  8. Ride Management
- Created backend routes to **generate and manage ride requests**.
- Captains can view and respond to ride requests in real time.
- Implemented distance and fare estimation logic.

###  9. Final Integration & Testing
- Connected all modules — user, captain, rides, and map — into a complete working app.
- Performed end-to-end testing to ensure smooth login, ride creation, and UI flow.

---

##  Tech Stack

| Layer | Technologies |
|-------|---------------|
| **Frontend** | React.js, Axios, CSS, Google Maps API |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (via Mongoose) |
| **Authentication** | JWT (JSON Web Token) |
| **External APIs** | Google Maps API |
| **Version Control** | Git & GitHub |

---

##  How to Run the Project Locally

If you’d like to try the app on your system, here’s how:

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/uber-clone-mern.git

