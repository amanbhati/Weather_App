# 🌤️ Zeotap Weather App

Welcome to the **Zeotap Weather App**, a real-time weather monitoring system that tracks, processes, and visualizes weather data for metro cities across India. Utilizing the OpenWeatherMap API, this project fetches, analyzes, and stores weather data, including temperature, weather conditions, and alerts based on user-defined thresholds.

---

## Table of Contents

1. [Features](#features)
2. [Tech Stack](#tech-stack)
3. [Project Structure](#project-structure)
4. [Installation](#installation)
5. [Environment Setup](#environment-setup)
6. [Usage](#usage)
7. [Future Enhancements](#future-enhancements)

---
 
## Features

- **Real-Time Data Retrieval**: Fetches weather data for major metro cities from the OpenWeatherMap API.
- **Daily Summaries**: Provides daily weather summaries for each city, covering conditions like temperature and weather status.
- **Alert System**: Notifies users when specific thresholds (temperature, conditions) are met.
- **Data Visualization**: Displays weather summaries and trends with easy-to-interpret graphs.
- **Customizable Cities**: Allows users to add new cities for real-time monitoring.

---

## Tech Stack

- **Frontend**: React, Chart.js
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **External API**: OpenWeatherMap API

---

## Project Structure

```plaintext
Zeotap-Weather-App/
├── frontend/               # Frontend (React)
├── backend/                # Backend (Express, MongoDB)
│   ├── config/             # Database connection
│   ├── models/             # MongoDB Schemas
│   ├── routes/             # API routes
│   ├── utils/              # Utility functions
├── .env                    # Environment variables
└── README.md               # Project documentation
```

---
## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/user/Zeotap-Weather-App.git
    cd Zeotap-Weather-App
    ```

2. **Install server dependencies**:
    ```bash
    cd backend
    npm install
    ```

3. **Install frontend dependencies**:
    ```bash
    cd ../frontend
    npm install
    ```

---

## Environment Setup

1. **Configure Environment Variables**:  
   Create a `.env` file in the root folder with the following variables:
    ```plaintext
    MONGO_URI=<Your MongoDB URI>
    API_KEY=<Your OpenWeatherMap API Key>
    ALERT_THRESHOLD=<Your choice of temperature for alerts>
    ```

2. **Starting the Server**:
    ```bash
    cd backend
    npm start
    ```

3. **Starting the Client**:  
   In a separate terminal window:
    ```bash
    cd frontend
    npm start
    ```

---

## Usage

- **Homepage**: View weather data summaries and trends for major cities.
- **Add City**: Use the interface to add new cities for weather monitoring.
- **Weather Alerts**: Receive notifications based on user-defined temperature or weather conditions.

---

## Future Enhancements

- **User Authentication**: Implement user accounts for personalized weather tracking.
- **Historical Data Analysis**: Store and analyze past weather data for trend forecasting.
- **Mobile App**: Extend the project to mobile platforms for broader access.

---

## UI Screenshot

![UI Screenshot](https://github.com/user-attachments/assets/d8a259fb-69b4-488f-9d2d-4671f2b17d03)
