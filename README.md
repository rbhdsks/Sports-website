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

This is a full-stack booking application developed for a sports technology company's operations team. The application allows center managers to view and create bookings for various sports facilities. The project is developed as per the requirements provided, focusing on core functionality with a simple and intuitive user interface.

---

## Project Overview

The application consists of:

- **Backend**: A RESTful API built with Node.js and Express, using MongoDB as the database.
- **Frontend**: A React application that interacts with the backend APIs.
- **Features**:
  - Centers can manage multiple sports and resources.
  - View bookings for a specific center, sport, and date.
  - Create new bookings while preventing double bookings.
  - Simple UI for operations team to manage bookings.

---

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- **Node.js** (v14 or later)
- **npm** (Node Package Manager)
- **MongoDB** (Local installation or access to MongoDB Atlas)
- **Git** (for cloning the repository)

---

## Installation

### Backend Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/rbhdsks/Sports-website/
   cd booking-app/backend
