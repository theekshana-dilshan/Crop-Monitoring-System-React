# Crop Monitoring System

## Introduction

Green Shadow (Pvt) Ltd. is a mid-scale farm specializing in root crops and cereals. The company operates at both national and international levels and is renowned for high-quality production. Due to recent expansion and a transition to large-scale production, the management has decided to implement a **Crop Monitoring System** to systematize field operations, crop tracking, and asset management.

## System Overview

The Crop Monitoring System is a **full-stack web application** with the following components:

- **Frontend:** Developed using React.js.
- **Backend:** Powered by Node.js with Express.
- **Database:** Uses MongoDB for storing system data.
- **Authentication:** Implements JWT-based authentication and role-based access control.
- **API Communication:** RESTful API endpoints for seamless interaction between the frontend and backend.

## Key Functionalities

### 1. User Access Management

Users can log into the system under the following roles:

- **Manager:** Oversees operations and ensures smooth workflow.
- **Administrative:** Manages data related to staff, vehicles, and equipment.
- **Scientist:** Tracks and monitors crop growth, field conditions, and observations.

Other users (e.g., workers) will not have direct access to the system but their data will be managed within respective modules.

### 2. CRUD Operations

The system enables authorized users to **Create, Read, Update, and Delete (CRUD)** data across various entities:

- **Crop Data:** Includes details such as crop type, growth stage, total extent, and field observations.
- **Non-Crop Data:** Manages human resources, equipment, and vehicles.

## Core Services

1. **Field Service:** Manages fields designated for specific crop types.
2. **Crop Service:** Handles crop-related information, including type, growth stage, and observations.
3. **Staff Service:** Manages human resources and their assignments.
4. **Log Monitoring Service:** Records and tracks crop-related observations and activities.
5. **Vehicle Service:** Oversees vehicle allocation and management.
6. **Equipment Service:** Manages agricultural equipment used in various operations.
7. **Auth Service:** Provides user authentication and access control.

## Technology Stack

- **Frontend:** React.js, Redux (for state management), Tailwind CSS/Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB with Mongoose ORM
- **Authentication:** JSON Web Tokens (JWT)
- **API Testing:** Postman, Jest (for backend testing)

## Installation & Setup

### Prerequisites

Ensure you have the following installed:

- **Node.js** (v16+)
- **MongoDB** (local or cloud-based)
- **npm** or **yarn** package manager

### Backend Setup

```sh
cd backend
npm install
npm start
```

### Frontend Setup

```sh
cd frontend
npm install
npm start
```

## Future Enhancements

- **Mobile App Integration**: A React Native app for field operations.
- **AI-powered Crop Health Analysis**: Using ML models to assess crop conditions.
- **Weather API Integration**: Real-time weather data for better decision-making.

## License

This project is licensed under the MIT License.

