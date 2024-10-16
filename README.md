# Booking App for Sports Facilities

**College ID Number**: IIB2021002  
**Name**: Nitesh Kumar Shah

---

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [Running the Application](#running-the-application)
  - [Running the Backend Server](#running-the-backend-server)
  - [Running the Frontend App](#running-the-frontend-app)
- [Deployment](#deployment)
  - [Backend Deployment](#backend-deployment)
  - [Frontend Deployment](#frontend-deployment)
- [Assumptions and Limitations](#assumptions-and-limitations)
- [Dependencies](#dependencies)
- [Usage Instructions](#usage-instructions)
- [Deployed Application Links](#deployed-application-links)
- [Contact Information](#contact-information)

---

## Introduction

This is a full-stack booking application developed for a sports technology company's operations team. The application allows center managers to view and create bookings for various sports facilities, ensuring there are no double bookings for the same court and time slot.

## Project Overview

The app handles multiple centers, multiple sports at each center, and multiple courts or resources for each sport. Center managers can view bookings and create new ones for any sport at their facility.

---

## Prerequisites

- Node.js installed
- MongoDB installed or a cloud database like MongoDB Atlas
- Git (optional for version control)

---

## Installation

### Backend Setup

1. Clone the repository and navigate to the backend directory:

   ```bash
   git clone <repo-link>
   cd booking-app-backend

Install the required dependencies:

bash
Copy code
npm install
Set up your MongoDB connection in the .env file:

env
Copy code
MONGO_URI=your-mongodb-uri
Run the backend server:

bash
Copy code
npm start
Frontend Setup
Navigate to the frontend directory:

bash
Copy code
cd ../booking-app-frontend
Install the required dependencies:

bash
Copy code
npm install
Run the frontend development server:

bash
Copy code
npm start
Running the Application
Running the Backend Server
The backend server can be run using the following command in the booking-app-backend directory:

bash
Copy code
npm start
The server will run on http://localhost:5000 by default.

Running the Frontend App
The frontend app can be run using the following command in the booking-app-frontend directory:

bash
Copy code
npm start
The frontend app will run on http://localhost:3000 by default.

Deployment
Backend Deployment
You can deploy the backend using services like Heroku, AWS, or DigitalOcean.

Follow the respective platform's guide for deploying Node.js apps.

Frontend Deployment
You can deploy the frontend using services like Netlify or Vercel.

Follow the respective platform's guide for deploying React apps.

