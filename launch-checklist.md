# 🚀 Talla Launch Checklist (iOS + Android)

This document outlines everything required to turn Talla from a prototype into a real mobile application and publish it on the App Store and Google Play.

---

## 🧠 1. Product Requirements (MVP)

Before building, define the minimum features:

### Core Features
- User authentication (Google / Apple)
- User profile
- Location access (GPS)
- Nearby cafes (map + list)
- Check-in system (with verification)
- Trend score (out of 10)
- Points & streak system
- Basic feed (posts)
- Add friends

### Phase 2 Features
- Chat system
- Notifications
- Reporting/blocking users
- Admin moderation dashboard

---

## 🛠 2. Technical Requirements

### Mobile App
Choose ONE:
- React Native (recommended)
- Flutter

---

### Backend
- Node.js / NestJS

Handles:
- Authentication
- Users
- Check-ins
- Friends
- Points system

---

### Database
- PostgreSQL

Stores:
- users
- cafes
- check-ins
- posts
- messages
- friendships

---

### Maps & Location
- Google Maps SDK or Mapbox

---

### Real-time Features
- Firebase OR WebSockets

Used for:
- live check-ins
- chat
- hotspot updates

---

### Media Storage
- Cloud storage (images/posts)

---

## 🔐 3. Legal & Store Requirements

You MUST have:

- Privacy Policy
- Terms of Service
- Support email
- Data usage explanation

---

### Permissions Needed
- Location (for nearby cafes)
- Camera (for posts)
- Photos (upload content)
- Notifications

---

## 🛡 4. Safety Requirements (VERY IMPORTANT)

Since Talla is social:

- Report user feature
- Block user feature
- Content moderation
- Anti-fake check-in system

---

## 📱 5. App Store Requirements (iOS)

You need:

- Apple Developer Account ($99/year)
- App Store Connect setup
- App icon
- Screenshots (iPhone sizes)
- App description
- Privacy policy URL
- TestFlight testing

---

## 🤖 6. Google Play Requirements (Android)

You need:

- Google Play Console account ($25 one-time)
- App icon
- Screenshots
- App description
- Privacy policy
- Signed app bundle (.aab)

---

## 📦 7. Build Requirements

### iOS
- Build using Xcode
- Upload via App Store Connect

### Android
- Generate .aab file
- Upload to Google Play Console

---

## 🎨 8. Design Assets

Prepare:

- App icon
- Splash screen
- Screenshots (5–8 screens)
- App preview images
- Logo (Talla branding)

---

## 🧪 9. Testing

Before publishing:

- Test login
- Test location accuracy
- Test check-in system
- Test feed & posts
- Test crashes
- Test performance

---

## 🚧 10. Common Rejection Reasons

Avoid:

- Broken login
- Fake location/check-ins
- Missing privacy policy
- No moderation system
- App crashes
- Empty content

---

## 🧩 11. Talla-Specific Needs

- Saudi-only location filtering
- Cafe database (initial dataset)
- Hotspot clustering logic
- Trend algorithm working
- Anti-cheat check-in system

---

## 🚀 12. Launch Plan

### Phase 1 (MVP Launch)
- Core features only
- Limited cities (Riyadh, Jeddah, Khobar)

### Phase 2
- Chat
- Notifications
- Social growth

### Phase 3
- AI recommendations
- Business dashboards
- Monetization

---

## 💡 Final Note

Talla is not just an app.

It is a real-time social platform built around:

- location
- trends
- culture
- people

The goal is to make Talla the default app for:

👉 "وين الطلّة اليوم؟"
