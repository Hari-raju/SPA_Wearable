# ⌚ Smart Protector – Wear OS Companion App

The **Wear OS Companion App** is an extension of the Smart Protector Application, designed to provide **continuous, on-wrist health and safety monitoring** for elderly users.  
It works alongside the main Android mobile app to detect emergencies in real time and notify caregivers instantly.

---

## 📽 Demo Videos

### 🛡 Fall Detection, Heart Rate Alert, and Watch Removal Alert
Demonstrates real-time fall detection, abnormal heart rate detection, and watch removal detection from the wearable, with alerts sent instantly to the caregiver’s phone.  
▶ [Watch Video](https://github.com/user-attachments/assets/3bd29c1d-7a73-46b0-aaf5-c5b79cbcfe9f)

---

### ⚙ Continuous Fall Detection Service Check
Shows the background fall detection service running continuously on the wearable to ensure uninterrupted monitoring.  
▶ [Watch Video](https://github.com/user-attachments/assets/cbbec438-5394-4434-b98d-3fae74764eb3)

---

## ✨ Key Wearable Features

- 📉 **Fall Detection** – Uses accelerometer, gyroscope, and magnetometer sensors to detect sudden motion changes.
- ❤️ **Heart Rate Monitoring** – Continuously tracks heart rate and alerts caregivers if abnormal thresholds are exceeded.
- ⌚ **Watch Removal Detection** – Uses proximity sensor to detect if the wearable has been removed and triggers an alert.
- 🔄 **Seamless Mobile Sync** – Transfers sensor event data to the Elder’s mobile app via **Data Layer API**.
- 🚨 **Automatic Emergency Alerts** – Follows the same Elder notification → 30-second timeout → Caregiver FCM alert logic as the main app.

---

## 🛠 Tech Stack

- **Platform:** Wear OS (Jetpack Compose)
- **Language:** Kotlin
- **APIs & Frameworks:**  
  - Data Layer API (Wear ↔ Mobile communication)  
  - Android Foreground Services (continuous monitoring)  
  - SensorManager (Accelerometer, Gyroscope, Magnetometer, Heart Rate, Proximity)  
- **Backend:** Firebase Cloud Messaging (FCM) for emergency alert delivery

---

## 🚀 How It Works

1. **Continuous Monitoring** – Sensors on the smartwatch constantly monitor for falls, abnormal heart rate, and watch removal.
2. **Local Elder Alert** – When an abnormal event occurs, the Elder receives an on-watch notification for confirmation.
3. **Emergency Escalation** – If there’s no response within 30 seconds, the alert is sent to the Caregiver’s phone via FCM.
4. **Data Sync** – Event details and status are sent to the Elder’s mobile app using the Data Layer API.

---

## 📌 Project Context

Originally built as part of the **Smart Protector Android App**, this Wear OS companion module was added in the recent project phase to enhance **24/7 health and safety tracking** directly from the user’s wrist.

---

## 📜 License

This project is for academic and demonstration purposes. All rights reserved.
