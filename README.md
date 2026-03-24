# 🎮 SKILIO Platform

SKILIO is a scenario-based interactive learning platform designed for kids.  
It combines storytelling and gamification to teach real-life decision-making skills in a fun and engaging way.

---

## 🚀 Features

- 📖 Interactive story-based missions  
- ⚖️ Decision-making with real consequences  
- 🏆 Gamification system (XP, levels, badges, streaks)  
- 🧍 Customizable avatars  
- 🌍 Multiple worlds (space, sea, forest)  
- 👨‍👩‍👧 Parent dashboard to track progress  

---

## 🧠 Problem

Traditional learning methods fail to engage children and do not provide real-life decision-making practice.

---

## 💡 Solution

SKILIO solves this by:
- Using gamified storytelling  
- Allowing kids to make choices and see consequences  
- Providing rewards and progression systems  

---

## 🏗️ Tech Stack

### Frontend
- React + Vite  

### Backend
- FastAPI  

### Database
- SQLite  

### Communication
- REST API (HTTP)  

---

## 🔄 System Architecture

Frontend (React) → API Requests → Backend (FastAPI) → Database (SQLite)

---

## 👶 User Journey

1. Create avatar (name + color)  
2. Choose a world  
3. Start a mission  
4. Read story & make decisions  
5. Get instant feedback  
6. Earn rewards & track progress  

---

## 🎯 Gamification System

- XP system for progress tracking  
- Coins for rewards  
- Levels & streaks  
- Instant feedback  

---

## 👨‍👩‍👧 Parent Dashboard

- Track child progress  
- View decisions & missions  
- Monitor skills and behavior  
- See rewards and achievements  

---

## ⭐ What Makes SKILIO Unique

- Scenario-based learning (not passive)  
- Real decision-making with consequences  
- Emotional + practical skill development  
- Parent-child connection  
- Fully gamified experience  

---

## ⚙️ How to Run the Project

### Backend
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
