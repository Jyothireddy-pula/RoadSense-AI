
# 🚧 RoadSense AI  
### An AI-Powered Pothole-Aware Navigation & Road Safety Platform  
*(Advanced Extension of iWatchRoadv2)*

## 📌 Overview
RoadSense AI is a real-world, AI-driven road safety and navigation system designed to detect potholes, warn drivers in real time, and support government road maintenance workflows

Built as an advanced extension of iWatchRoadv2, this project bridges the gap between infrastructure monitoring and citizen safety using AI, GPS, and modern web technologies.

---

## 🎯 Problem Statement
Road accidents caused by potholes and damaged roads are a major safety concern. Current systems rely on manual inspection and do not warn drivers in advance. There is a lack of real-time intelligence for both citizens and government authorities.

---

## 💡 Solution
RoadSense AI automatically detects potholes using AI, maps them using GPS, alerts drivers while traveling, and provides actionable dashboards for authorities to manage road repairs efficiently.

---

## 🚀 Key Features

### 🧠 AI-Based Pothole Detection
- YOLOv8 deep learning model
- Dashcam video processing
- Severity classification (Low / Moderate / High)

### 🧭 Pothole-Aware Navigation (Core Innovation)
- Live GPS tracking
- Voice alerts: “Pothole ahead in 50 meters. Slow down.”
- Real-time warnings during travel

### 🎨 Road Glow Visualization
- Color-coded roads based on severity
- Interactive Leaflet map

### 👥 Crowdsourced Validation
- Users can confirm or mark potholes as fixed
- Confidence-based self-correcting system

### 🏛️ Government Dashboard
- Repair lifecycle tracking
- Contractor assignment
- Data-driven road maintenance

### 🔮 Predictive Road Risk
- Predicts pothole-prone areas using historical data
- Helps prevent damage before it occurs

---

## 🧠 System Architecture
Dashcam → AI Detection → GPS Mapping → Database → Route Check API → Driver Alerts → Analytics

---

## 🛠️ Technology Stack

**Backend:** Django, Django REST Framework, PostgreSQL, Geopy  
**Frontend:** React, TypeScript, Leaflet, Web Speech API  
**AI/ML:** YOLOv8, OpenCV, Scikit-learn  
**DevOps:** Docker, GitHub Actions, AWS / Render / Vercel

---

## ▶️ How It Works
1. Dashcam video is uploaded
2. AI detects potholes and stores GPS data
3. Driver starts navigation
4. System checks nearby potholes continuously
5. Voice alert warns driver before hazard
6. Authorities use dashboards for action

---

## 🎥 Demo & Proof
A demo video showing real GPS-based alerts and navigation is included in the demo folder.

---

## 🌍 Real-World Feasibility
- Works on smartphones and browsers
- Scalable city by city
- Suitable for smart city and government deployment

---

## 🧾 Interview One-Line Explanation
“I built RoadSense AI, an AI-powered pothole-aware navigation system that detects road hazards, alerts drivers in real time, and helps authorities manage road infrastructure efficiently.”

---

## 🔮 Future Enhancements
- Mobile app (Android/iOS)
- Offline navigation
- Google Maps integration
- Advanced analytics dashboards

---

## 📜 License
Open-source, suitable for academic and non-commercial use.

