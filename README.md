# ![Coachy Logo](./src/assets/Logo.png) Coachy - E-Fitness Web Application

*A React-based fitness coaching platform with AI-powered workout
feedback*

![Landing Page](./src/assets/landingpage.png)


## 📌 Overview

Coachy is a modern e-fitness platform built using **React**,
**Firebase**, and **Python FastAPI**.\
It aims to make online coaching accessible to everyone by providing
preset workout plans, nutrition tracking, activity dashboards, and
**real-time AI camera feedback** during workouts.

This project was developed as part of the **Digital Egypt Pioneers
Initiative (DEPI)**.

------------------------------------------------------------------------

## 🚀 Features

### 🔐 Authentication

-   Secure login & registration using Firebase Authentication.
-   User profile and goal management.

### 🏋️ Workouts & AI Coaching

-   Weekly preset workout plans.
-   Exercise library with descriptions & demos.
-   **AI camera session** for real-time exercise feedback via FastAPI
    backend.

### 🍎 Nutrition Tracking

-   Predefined meal plans for different goals.
-   Daily calorie logging and consumption history.

### 📊 Progress Dashboard

-   Visual charts for weight change over time.
-   Progress photo uploads (front & side).
-   Calorie burn and activity insights.

### ☁️ Backend & Cloud Services

-   Firebase Firestore for scalable real-time database operations.
-   Python FastAPI microservice for AI video stream analysis.

------------------------------------------------------------------------

### 🌐 Live Demo  
Visit the website here: **[Coachy Web App](https://coachyfit.web.app/)**  

------------------------------------------------------------------------


## 🛠️ Tech Stack

### **Frontend**

-   React.js (TypeScript)
-   Redux Toolkit
-   Tailwind CSS
-   Framer Motion

### **Backend**

-   Firebase Auth & Firestore
-   Python FastAPI (AI service)

### **Deployment**

-   Firebase Hosting (Frontend)
-   High-performance cloud hosting (AI backend)

------------------------------------------------------------------------

## 🗂️ Project Structure

    src/
     ├── components/        # Reusable UI components
     ├── firebase/          # Firebase configuration
     ├── pages/             # Dashboard, Workouts, Nutrition, Profile
     ├── services/          # API integrations (Python backend)
     ├── store/             # Redux slices
     └── assets/            # Images & UI assets

------------------------------------------------------------------------

## 📥 Installation & Setup

### 1. Clone the repository

``` bash
git clone <repo-url>
cd coachy
```

### 2. Install dependencies

``` bash
npm install
```

### 3. Create a `.env` file and add Firebase + API configurations

    VITE_FIREBASE_API_KEY=...
    VITE_FIREBASE_AUTH_DOMAIN=...
    VITE_FIREBASE_PROJECT_ID=...
    VITE_AI_BACKEND_URL=...

### 4. Run the development server

``` bash
npm run dev
```

------------------------------------------------------------------------

## 🌐 System Architecture

### **Client Application**

-   React handles the UI, routing, authentication state, and primary
    logic.

### **Data Layer**

-   Firestore stores:
    -   User profile
    -   Nutrition logs
    -   Workout history
    -   Progress photos
    -   Weight tracking

### **AI Microservice**

-   React streams camera footage to FastAPI.
-   Backend analyzes user movement and returns real-time feedback.

------------------------------------------------------------------------

## 📊 KPI Focus Areas

-   **AI Response Time** \< 200ms\
-   99.9% Reliability & Uptime
-   High user retention within first 7 days
-   Accurate calorie tracking & progress monitoring

------------------------------------------------------------------------

## 🧪 Testing Strategy

-   Manual UI & UX testing (authentication, flows, responsiveness).
-   AI testing under variable lighting, angles & real-world exercise
    scenarios.
-   Functional validation of CRUD operations with Firestore.

------------------------------------------------------------------------

## 📱 User Guide

### ▶ Starting a Workout

1.  Login → Dashboard
2.  Go to **Workouts**
3.  Select a program
4.  Start **AI Camera Session**
5.  Follow feedback and log completed sets

### 🍽 Tracking Nutrition

1.  Go to **Nutrition**
2.  Pick a meal plan
3.  Mark meals as consumed

### 📈 Viewing Progress

-   Open **Dashboard** for charts
-   Upload progress photos
-   Track weight & historical data

------------------------------------------------------------------------

## 🧩 Frontend Routes

  Route                    Description
  ------------------------ ---------------------
  `/login`                 User Authentication
  `/dashboard`             Stats Overview
  `/workouts`              AI Camera Session
  `/nutrition`             Meal Logging
  `/profile`               User settings

------------------------------------------------------------------------

## 📘 Conclusion

Coachy delivers a complete digital fitness experience by combining:

-   A modern React interface
-   Secure and scalable Firebase backend
-   AI-driven real-time coaching using FastAPI

The modular architecture supports future expansion, improved AI models,
and scaling to thousands of users. Coachy bridges the gap between
traditional coaching and digital tracking, empowering users to train
smarter and stay consistent.

