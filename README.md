# Kreeda-Prerana – Sports Talent Scout App

## Overview

Kreeda-Prerana is an Android-based sports talent identification application designed to help schools and physical education teachers track, monitor, and identify talented young athletes. The app focuses on rural and grassroots-level sports development by digitally recording student athletic performance and creating a long-term performance history.

The application helps teachers and coaches discover hidden sports talent and encourage students to improve through performance tracking, rankings, and milestone achievements.

---

# Problem Statement

Many talented students in rural schools do not receive proper recognition because there is no structured system to record and monitor their sports performance. Physical education teachers often rely on manual observations, making it difficult to identify students with long-term athletic potential.

As a result, many young athletes lose opportunities to participate in district, state, or national-level competitions.

Kreeda-Prerana aims to bridge this gap by providing a digital sports scouting and performance tracking platform for schools.

---

# Features

## Athlete Profile Management
- Create athlete profiles
- Store student details such as:
    - Name
    - Age
    - Gender
    - Class
    - Primary sport
- Track athlete progress over time

---

## Performance Trial Logger
- Record athletic performance tests
- Stopwatch-based sprint timing
- Distance measurement logging
- Supports activities such as:
    - Running
    - Long Jump
    - High Jump
    - Kabaddi fitness drills
    - Athletics training

---

## Talent Curve Analytics
- Displays athlete performance history
- Tracks improvement over multiple trials
- Generates easy-to-understand progress graphs
- Helps identify consistently improving athletes

---

## Leaderboard System
- School-level ranking system
- Displays top-performing students
- Encourages healthy sports competition
- Automatic sorting based on best performance

---

## Milestone Badge System
- Awards achievement badges automatically
- Examples:
    - “District Level Ready”
    - “State Potential Athlete”
    - “Sprint Champion”
- Motivates students to improve performance

---

## Batch Entry System
- Allows teachers to add performance data for an entire class
- Supports quick entry for up to 30 students
- Reduces manual work during sports trials

---

## AI Sports Assistant
- AI-powered chatbot using Gemini API
- Provides:
    - Sports guidance
    - Training tips
    - Fitness suggestions
    - Motivation support
- Helps students and teachers with sports-related queries

---

# Technologies Used

- Kotlin
- Android Studio
- Jetpack Compose
- Room Database
- Firebase Authentication
- Cloud Firestore
- Gemini AI API
- MPAndroidChart
- Material Design Components

---

# Application Flow

1. User logs into the application
2. Teacher creates athlete profiles
3. Performance trials are recorded
4. App stores athlete performance history
5. Talent Curve graph displays progress
6. Leaderboard ranks top athletes
7. Milestone badges are awarded automatically
8. AI assistant provides sports guidance and support

---

# Technical Implementation

## High-Precision Timer
- Chronometer implementation for sprint timing
- Accuracy up to two decimal places

---

## Local Database Management
- Room Database stores athlete records
- Maintains performance history offline

---

## Cloud Integration
- Firebase Authentication for secure login
- Cloud Firestore for syncing athlete data

---

## Analytics & Ranking
- Sorting algorithms generate leaderboards
- Performance comparison between athlets

---

## Graph Visualization
- Talent Curve graphs show progress trends
- Visual analysis of athlete improvement

---

# Project Structure

```text
app/
├── manifests/
├── kotlin+java/
│   └── com.example.kreedaprerana/
│       ├── data/
│       │   ├── local/
│       │   │   ├── dao/
│       │   │   ├── database/
│       │   │   └── entities/
│       │   │
│       │   ├── remote/
│       │   │   ├── firebase/
│       │   │   └── gemini/
│       │   │
│       │   └── repository/
│       │
│       ├── di/
│       │
│       ├── domain/
│       │   ├── model/
│       │   ├── repository/
│       │   └── usecase/
│       │
│       ├── network/
│       │
│       ├── ui/
│       │   ├── auth/
│       │   ├── athlete/
│       │   ├── batchentry/
│       │   ├── dashboard/
│       │   ├── leaderboard/
│       │   ├── milestones/
│       │   ├── navigation/
│       │   ├── onboarding/
│       │   ├── performance/
│       │   ├── profile/
│       │   ├── splash/
│       │   ├── statistics/
│       │   ├── talentcurve/
│       │   ├── chatbot/
│       │   ├── settings/
│       │   └── theme/
│       │
│       ├── util/
│       │   ├── constants/
│       │   ├── extensions/
│       │   └── validation/
│       │
│       ├── KreedaPreranaApp.kt
│       └── MainActivity.kt
│
├── res/
│   ├── drawable/
│   ├── mipmap/
│   ├── values/
│   └── xml/
│
└── Gradle Scripts/

git clone https://github.com/Akshitha-K1/KreedaPrerana.git

---

# Open Project

1. Open Android Studio  
2. Click on **Open**  
3. Select the cloned project folder  

---

# Sync Gradle

- Allow Android Studio to download dependencies  
- Click **Sync Project with Gradle Files** if required  

---

# Run Application

1. Connect an Android device or start an emulator  
2. Click the **Run ▶** button in Android Studio  
3. Wait for the application to build and launch  

---

# Demo Link

[Live Demo](https://appetize.io/app/b_hrcjgn2jd4lgtxizc57cwk46eu)

---

---

# App Screenshots

## Login Page
![Login](images/Login.png)

---

## Home Screen
![Home](images/Home.png)

---

## Talent Curve Page
![Talent Curve](images/TalentCurve.png)

---

## Log Trial Page
![Log Trial](images/LogTrial.png)

---

## Timer Page
![Timer](images/Timer.png)

---

## Leaderboard Page
![Leaderboard](images/Leaderboard.png)

---

# Future Improvements

- AI-based athlete performance prediction
- Multi-school competition management
- State and district level athlete database
- Wearable fitness tracker integration
- Video-based performance analysis
- Real-time coach and scout connectivity
- Cloud backup and synchronization
- Advanced analytics dashboard for coaches
- Multi-language support for rural schools
- Offline mode for low internet areas

---

# Impact Goals

- Identify hidden sports talent in rural schools
- Support grassroots sports development
- Encourage physical fitness and sports participation
- Create digital performance records for athletes
- Help students prepare for district and state competitions
- Support initiatives like Khelo India
- Promote equal opportunities for rural athletes

---

# Author

Chaithanya S

---

# License

This project is developed for educational and internship evaluation purposes.

---
