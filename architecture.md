# 🏗 Talla System Architecture

## Overview

Talla is designed as a real-time, location-based social platform.

The system consists of:

- Mobile/Web frontend
- Backend API
- Real-time services
- Location services
- Database

---

## 🧩 Components

### 1. Frontend
- Next.js (current prototype)
- Future: React Native (mobile app)

Handles:
- UI/UX
- User interaction
- Location access
- API communication

---

### 2. Backend API
- Node.js / NestJS (planned)

Handles:
- Authentication
- User profiles
- Check-ins
- Friend system
- Points & streaks

---

### 3. Real-time Engine
- WebSockets / Firebase

Handles:
- Live check-ins
- Hotspot updates
- Chat system

---

### 4. Database
- PostgreSQL + PostGIS

Stores:
- Users
- Cafes
- Check-ins
- Locations
- Social data

---

### 5. Trend Algorithm

Trend score (out of 10) is based on:

- Number of check-ins
- Recency of visits
- Repeat visitors
- Social engagement
- Friend activity

---

## 🔥 Key Idea

The system transforms **physical locations into live digital hotspots**.

---

## 🚀 Future Expansion

- AI recommendation engine
- Predictive trend analysis
- Business dashboards for cafes
