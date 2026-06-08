# MindMate 🤖💙

**AI-Powered Personalized Mental Health Companion for College Students**


> A calming, intelligent, and privacy-first mobile app that helps students track their mood, analyze their emotions, and feel better every day.

---

## 📋 Overview

**MindMate** is an intelligent mobile application designed to support college students in managing stress, anxiety, and emotional well-being. It combines **daily mood tracking**, **AI-powered journal analysis**, and **interactive wellness tools** to provide personalized mental health support.

Built as a college mini-project, MindMate focuses on **privacy**, **simplicity**, and **real student needs**.

---

## 🎯 Problem Statement

College students face increasing mental health challenges due to academic pressure, social isolation, and future uncertainty. Nearly **40-50%** of Indian college students experience moderate to severe psychological distress. However, professional help is often inaccessible due to cost, stigma, and limited availability.

MindMate bridges this gap by offering an **always-available, confidential, and intelligent digital companion**.

---

## ✨ Key Features

- 🔐 Secure Authentication (Email & Google)
- 📊 Daily Mood Tracking with Streak Counter
- 📝 Text & Voice Journaling
- 🧠 Real-time **On-device AI Sentiment Analysis**
- 📈 Personalized AI Insights & Mood Patterns
- 🧘‍♂️ Interactive Coping Tools (Guided Breathing, Grounding Exercises)
- 📱 Beautiful Mood History Dashboard with Charts
- 🚨 Smart Crisis Detection + India-specific Helplines
- 🎨 Calm, Soothing & Modern UI/UX

---

## 📊 Use Case Diagram

![MindMate Use Case Diagram](https://github.com/Akil-Ai/Mind-Mate/blob/main/Usecase%20diagram.png)

> *Detailed Use Case Diagram showing all major features and interactions*

*(Replace the link above with the actual image path after uploading the diagram to your repo)*

---

## 🧩 Modules

| Module                    | Description |
|--------------------------|-----------|
| Authentication           | User registration, login & profile management |
| Mood Tracking            | Daily mood logging with visual feedback |
| Journaling               | Text & voice entries with AI analysis |
| AI Insights              | Sentiment analysis & personalized recommendations |
| Wellness Tools           | Breathing exercises, motivational content & calm sessions |
| Dashboard                | Mood trends and history visualization |
| Crisis Support           | Automatic distress detection & helpline suggestions |
| Settings                 | Privacy controls & theme customization |

---
## 🗄️ Database Design

### Entity Relationship (ER) Diagram

![MindMate ER Diagram](https://github.com/Akil-Ai/Mind-Mate/blob/main/er%20diagram.png)

*(Upload the generated ER Diagram image here)*

### Firestore Database Structure (NoSQL)

Collections:

1. users
   ├── {userId}
         ├── name
         ├── email
         ├── age
         ├── gender
         ├── createdAt
         ├── streakCount
         └── lastMoodDate

2. moodLogs (Sub-collection under user)
   ├── {logId}
         ├── moodScore (1-5)
         ├── moodEmoji
         ├── note
         ├── timestamp

3. journalEntries (Sub-collection under user)
   ├── {entryId}
         ├── content
         ├── sentiment (Happy/Anxious/Sad/Stressed/Neutral)
         ├── confidence
         ├── timestamp

4. insights (Sub-collection under user)
   ├── {insightId}
         ├── title
         ├── description
         ├── type (weekly/monthly)
         ├── timestamp

5. helplines (Global collection)
   ├── {id}
         ├── name
         ├── number
         ├── description
---

## 🛠️ Technologies Used

- **Frontend**: Flutter (Cross-platform)
- **Backend**: Firebase (Auth + Firestore)
- **Database**: Firebase Firestore
- **AI/ML**: TensorFlow Lite / Hugging Face (On-device)
- **State Management**: Provider / Riverpod
- **Charts**: fl_chart
- **Animations**: Lottie

---

## 🚀 Future Enhancements

- Wearable device integration (Heart rate monitoring)
- AI Chatbot using LLMs
- Multilingual support (English + Tamil)
- Gamification & Rewards system
- Anonymous peer community
- College counseling integration

---

## 📌 Note

**MindMate is a supportive companion app and is not a substitute for professional mental health treatment.**

---

## 📄 License

This project is developed as part of a college mini-project.

---

**Made with ❤️ for better student mental health**
