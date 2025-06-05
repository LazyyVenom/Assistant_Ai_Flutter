# 📱 Actual Useful Assistant – Flutter App

A fully free, intelligent, and cross-platform productivity and wellness assistant built with Flutter. Designed to help you organize tasks, manage time, build habits, and stay motivated—right from your mobile device.

---

## 📌 Overview

This Flutter app is the mobile companion to the **Actual Useful Assistant** ecosystem. It integrates seamlessly with the shared Firebase backend used by the desktop and CLI apps (macOS/Windows). The mobile app focuses on accessibility, quick interaction, habit-building, gamification, and on-the-go tracking.

---

## 🌟 Key Features

### 🗂️ Task & Time Management
- **Task Lists** with categories, priorities, and deadlines  
- **Daily & Weekly Planner** with scheduling and visualization  
- **Time Blocking** to dedicate focused slots for deep work  
- **Pomodoro / 90-Minute Rule Timer** for time management  
- **Smart Suggestions** for today’s tasks based on urgency, priority, and past performance  

### 📈 Progress Tracking & Gamification
- **Day Score & Mood Tracker** – rate your day and emotional well-being  
- **Habit Streaks** – track consistency with daily habits  
- **Weekly/Monthly Analytics** – view visual summaries of your time and productivity  
- **XP & Level System** – earn experience points for completing tasks, journaling, learning, etc.  
- **Achievements & Badges** – unlock badges for milestones and consistent behavior  
- **Progress Dashboard** – visual feedback on goals, habits, and wellness trends  
- **Leaderboard (Optional)** – compare productivity and consistency with friends (if enabled)

### 🤖 AI-Powered Assistance
- **Quick Rephrasing Tool** using Gemini API (for emails, texts, or notes)  
- **AI Chat Mode** for task guidance, idea generation, and planning  
- **Opportunity Seeker** scans goals/interests to suggest relevant content or trends  

### 🧠 Learning & Notes
- **Notes & Flashcards System**  
- **Skill-building Flowcharts** for breaking down learning journeys  
- **Idea Journal** – capture creative thoughts and random ideas anytime  

### 🌱 Motivation & Wellness
- **Daily Quotes** – random or user-selected inspirations  
- **Motivational Video Library** – add/save videos and play in-app  
- **Work-Life Balance Score** – helps you reflect on daily burnout risk  
- **End-of-Day Journaling** and mental RAM clearing zone  

### 🔐 Personalization & Sync
- **User Profiles** for preferences, settings, and personalized AI prompts  
- **Firebase Auth** for secure sign-in via Email, Google, etc.  
- **Realtime Data Sync** across mobile, desktop (PyQt5), and CLI  
- **Offline-first Support** for journaling and task editing  

---

## 🧰 Tech Stack

| Layer          | Technology                          |
|----------------|--------------------------------------|
| **UI**         | Flutter + Material Design            |
| **State Mgmt** | Riverpod / Provider (your choice)    |
| **Backend**    | Firebase Firestore, Auth             |
| **AI Layer**   | Gemini API (via REST)                |
| **Video**      | `video_player` Flutter package       |
| **Charts**     | `fl_chart` or `syncfusion_flutter_charts` |
| **Gamification** | Custom XP & Badge logic + Firestore |
| **Notifications** | `flutter_local_notifications`     |

---
