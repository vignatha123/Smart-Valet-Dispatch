# Smart Valet Parking Dispatch System

This project contains a presentation for a *Smart Valet Parking Dispatch System*, designed for an interview round.

It outlines how valet parking can be automated using a combination of sensors, geofencing, and real-time tracking to improve vehicle retrieval efficiency and user experience.

---

## 📄 Contents

- Smart_Valet_Dispatch_System.pdf - Main project presentation

---

## 📋 Overview

The system includes:
- A user app to request valet drop and retrieval
- Backend to track users, predict exit gates, and dispatch instructions
- BLE/Wi-Fi based gate sensors to assist indoor tracking
- A valet dashboard for staff to receive real-time dispatch info

---

## 🚦 Exit Gate Detection Logic

Technologies Used:
- *Wi-Fi / BLE Beacons*: For signal strength detection near gates
- *Geofencing*: For defining virtual exit zones
- *Motion Detection*: Using accelerometer and compass
- *Real-Time Updates*: To adapt predictions based on movement

---

## ⚙ Challenges & Solutions

| Challenge              | Solution                                |
|------------------------|------------------------------------------|
| GPS inaccuracy indoor  | Use Wi-Fi/BLE triangulation             |
| Sudden direction shift | Real-time tracking updates predictions  |
| Congested gates        | Backend re-routes valet dispatch        |

---

## 📱 Assumptions

- BLE/Wi-Fi beacons are installed at exits  
- Users have smartphones with sensors & internet  
- Valet staff use devices to receive instructions  
- Retrieval initiated by app or SMS

---

## 📌 Author

- *Vignatha*  
- Role: Candidate (Interview Round Submission)

---
