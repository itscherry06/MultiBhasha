# Agribot & Medibot

## Overview

**Agribot** and **Medibot** are intelligent chatbot applications designed to assist users in rural areas with critical information and learning support. Both bots focus on accessibility, low-bandwidth usage, and regional language support to reach underserved communities effectively.

---

## 1. Agribot

**Purpose:**  
Agribot provides farmers and rural communities with guidance on agriculture, crop management, pest control, weather updates, and best practices in regional languages.

**Features:**
- **Regional Language Support:** Lessons, advice, and notifications in local languages.  
- **Text & Voice Assistance:** Supports Text-to-Speech and Speech-to-Text for low literacy users.  
- **Offline Access:** Key lessons and resources available offline.  
- **Interactive Quizzes:** Test knowledge about farming practices.  
- **Progress Tracking:** Monitor learning and farming skill improvement.

**Technical Stack:**
- **Backend:** Python (Flask) / Node.js (Express)  
- **Database:** SQLite or Firebase Firestore (lightweight, offline-first)  
- **Front-end:** Android App / Web Application  
- **AI Integration:** Natural Language Processing for Q&A, TTS/STT services for audio lessons  

**Usage:**
1. Open the Agribot app or website.  
2. Select the regional language.  
3. Explore lessons, watch videos, and take quizzes.  
4. Offline resources are available in the “Download” section.  

---

## 2. Medibot

**Purpose:**  
Medibot assists users in understanding and managing common health conditions, with a focus on tuberculosis and chest-related illnesses, providing timely medical advice and educational resources.

**Features:**
- **Regional Language Support:** Health information delivered in local languages.  
- **Medical Q&A:** Ask about symptoms, prevention, and general guidance.  
- **Voice Assistance:** Supports audio explanations for non-literate users.  
- **Symptom Checker:** Basic guidance based on reported symptoms (not a replacement for professional diagnosis).  
- **Offline Access:** Key health resources available offline.

**Technical Stack:**
- **Backend:** Python (Flask) / Node.js (Express)  
- **Database:** SQLite or Firebase Firestore  
- **Front-end:** Android App / Web Application  
- **AI Integration:** Simple rule-based symptom detection + NLP for user queries  

**Usage:**
1. Open the Medibot app or website.  
2. Select your regional language.  
3. Ask questions or browse educational videos.  
4. Use offline resources when internet access is limited.  

---

## Common Notes

- **Video & Media Handling:** Heavy media files are stored externally (Firebase Storage / Cloud Storage) and referenced via URLs in the database to minimize payload.  
- **Security:** No personal data is stored; if user data is collected, it follows privacy best practices.  
- **Scalability:** Both bots are optimized for rural users with low-end devices and slow internet.  

---

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/agribot-medibot.git
