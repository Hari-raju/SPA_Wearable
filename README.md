# ⌚ Smart Protector – Wear OS Companion App

The **Wear OS Companion App** is part of the Smart Protector Application, designed to provide **continuous, on-wrist safety and health monitoring** for elderly users.  
It extends the mobile app with **real-time fall detection, heart rate monitoring, and watch removal alerts**, ensuring immediate caregiver notifications.

---

## 📽 Demo Videos

### 🛡 Fall Detection, Heart Rate Alert & Watch Removal Alert
Demonstrates wearable-based detection of falls, abnormal heart rate, and watch removal with instant caregiver alerts.

<video src="https://github.com/user-attachments/assets/3bd29c1d-7a73-46b0-aaf5-c5b79cbcfe9f" controls width="700"></video>

---

### ⚙ Continuous Fall Detection Service Check
Shows the always-on fall detection service running in the background on the wearable for uninterrupted monitoring.

<video src="https://github.com/user-attachments/assets/cbbec438-5394-4434-b98d-3fae74764eb3" controls width="700"></video>

---

## ✨ Key Wearable Features

- 📉 **Fall Detection** – Uses accelerometer, gyroscope, and magnetometer for motion analysis.  
- ❤️ **Heart Rate Monitoring** – Alerts caregivers when thresholds are exceeded.  
- ⌚ **Watch Removal Detection** – Detects removal using proximity sensor and sends alerts.  
- 🔄 **Wear ↔ Mobile Sync** – Data Layer API for instant event transfer to Elder’s mobile app.  
- 🚨 **Emergency Alerts** – Elder notification → 30s timeout → Caregiver FCM alert.

---

## 🛠 Tech Stack

- **Platform:** Wear OS (Jetpack Compose)  
- **Language:** Kotlin  
- **APIs:** Data Layer API, SensorManager, Foreground Services  
- **Backend:** Firebase Cloud Messaging (FCM)

---

## 🚀 How It Works

1. **Continuous Monitoring** via smartwatch sensors.  
2. **Local Elder Alert** on watch for confirmation.  
3. **Automatic Escalation** if no response in 30s.  
4. **Instant Sync** with Elder’s mobile app via Data Layer API.

---

## 📌 Project Context

Originally developed as a mobile-only solution, the **Wear OS companion** was added in a later phase to deliver **24/7 wrist-based monitoring** and faster emergency response.

---

## 📜 License

This project is for academic and demonstration purposes. All rights reserved.
