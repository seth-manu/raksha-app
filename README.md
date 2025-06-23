
# 🛡️ Raksha – Civil Defense Safety App

**Empowering citizens to stay safe and respond swiftly during emergencies.**  
Built for WWDC25 Hackathon | Bengaluru, India

---

## 🎯 Overview

**Raksha** is a privacy-first, offline-capable civil defense app designed to help citizens report threats, send SOS alerts, and receive real-time safety notifications—especially during high-stress situations like Operation Sindoor.

---

## 🚨 Key Features

| Feature | Description |
|--------|-------------|
| **One-Tap SOS** | Instantly sends your location to emergency contacts. |
| **Voice & Photo Reporting** | Quickly capture and report suspicious activity. |
| **Nearby Alerts** | Get notified about threats reported near you. |
| **Offline Mode** | Works without internet; syncs when back online. |
| **Apple Watch Support** | Silent alerts and haptic confirmations. |
| **Siri Shortcuts** | Voice-activated emergency triggers. |
| **Privacy-First** | No login, encrypted local storage, emergency PIN. |

---

## 👤 User Personas & Use Cases

- **College Student**: Sends SOS, records voice report, notifies nearby users.
- **Elderly Person**: Uses Siri to trigger silent SOS and background recording.
- **Nearby Citizen**: Receives alert, checks map, chooses safer route.

---

## 🧠 Technical Architecture

- **Frontend**: SwiftUI
- **Storage**: CoreData (local), CloudKit (public DB)
- **Location**: CoreLocation
- **Watch Support**: WatchKit
- **Voice Commands**: SiriKit
- **Offline Sharing**: MultipeerConnectivity (future scope)

---

## 👥 Team

- **Navin** – Watch App & Siri Integration  
- **Shahid** – Core Functionality & UI  
- **Vikas** – CloudKit, Offline Sync & Alerts

---

## 📱 Built With

- SwiftUI • CoreData • CloudKit • CoreLocation  
- WatchKit • SiriKit • MultipeerConnectivity (planned)

---

## 🔐 Privacy & Security

- No login or account required  
- Encrypted local storage  
- Emergency PIN & auto-delete features

---

## 📎 License

MIT License © 2025 Raksha Team

---

> “In emergencies, every second counts. Raksha ensures you're never alone.”

---

For detailed functional requirements, please refer to [requirements.md](requirements.md).
