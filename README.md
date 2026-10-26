# 🛡️ TrustNet Safety App

An Android application that provides instant help during emergencies. Users can send SOS alerts with live location to trusted contacts, even when offline via SMS.

**Developed by:** Khushboo Khatun & Sufiya Shabnam
**Department of Computer Engineering, Aligarh Muslim University (AMU)**

---

## 📖 Abstract
TrustNet Safety App is designed to provide quick, reliable and easy access to emergency assistance anytime, anywhere. It supports manual SOS, shake detection, emergency helplines and offline SMS support, so help can reach trusted contacts in critical situations.

## ✨ Key Features
- 🆘 **SOS with Sequential Calls:** Sends emergency SMS and calls trusted contacts one by one
- 📍 **GPS / Live Location Sharing:** Shares real-time location with trusted contacts
- 📳 **Shake to SOS:** Uses the accelerometer to detect shakes and trigger SOS
- ⏱️ **5-Second Countdown with Vibration & Undo:** Cancel the SOS before it is sent
- 👥 **Trusted Contacts:** Add, manage and alert your trusted contacts
- ☎️ **Emergency Helplines:** Quick access to police, ambulance and more
- 🕘 **SOS History:** Stores SOS logs locally using SQLite (Room)
- 📞 **Fake Call Simulation:** Simulated incoming call with ringtone and vibration
- 🌐 **Multi-Language Support:** English, Hindi, Hinglish

## 🛠️ Tech Stack
| Category | Technology |
|---|---|
| Frontend | Kotlin (Android), XML |
| Database | Room Database (SQLite) |
| Location | Google Maps API |
| SMS Service | Android SMS API |
| IDE | Android Studio |
| Other Tools | Git, GitHub |

## 🏗️ System Architecture
`User (Android Device)` → `TrustNet Safety App` → `Services (GPS, SMS, Maps)` → `Database (Room DB)` → `Trusted Contacts (receive alert)`

## 📸 Screenshots
| Home Dashboard | SOS Screen |
|---|---|
| ![home](screenshots/home.jpeg) | ![sos](screenshots/sos.jpeg) |![poster]_(screenshots/poster.jpeg)

## 🚀 How to Run
1. Clone the repo
   ```bash
   git clone https://github.com/gp6825/TrustNet-Safety-App.git
   ```
2. Open the project in **Android Studio**
3. Add your Google Maps API key in `local.properties`:
   ```
   MAPS_API_KEY=your_api_key_here
   ```
4. Let Gradle sync, then run on an emulator or a real device
5. Allow permissions when asked: **Location, SMS, Phone/Call**

> ⚠️ Shake detection, SMS and calls work best on a real device.

## 🔮 Future Scope
- Real-time chat with trusted contacts
- Cloud backup & data sync
- AI based risk detection & alerts
- Wearable device integration
- Web dashboard for emergency monitoring

## 💡 Innovation & Impact
- Offline functionality for real-time help
- Sequential calling to multiple contacts
- Shake detection using device sensors
- Faster response in emergencies, more safety and confidence

## 👩‍💻 Authors
- **Khushboo Khatun**
- **Sufiya Shabnam**

## 📄 License
This project is for educational purposes.
