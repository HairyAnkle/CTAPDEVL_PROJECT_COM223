# CTAPDEVL_PROJECT_COM223

# 📱 Network Spoofing Detection and Prevention of IoT Devices with Vulnerability Analysis

An Android-based mobile application designed to **detect and prevent ARP and DNS spoofing attacks**, **scan IoT devices** for open ports and vulnerabilities, and **generate security reports** — built using MVVM architecture.

---

## 📖 User Manual

### 🏁 Getting Started

1. **Install the APK** on any Android 9+ device.
2. **Connect your phone and other devices to the same network** (e.g., mobile hotspot).
3. Launch the app and **log in using Google Sign-In**.
4. Navigate using the **bottom navigation bar**.

---

## 📂 Features by Page

### 🚀 Splash Activity
- Launch screen showing the app's branding.

### 🔐 Login Page
- Firebase Google Sign-In
- Automatically redirects to the Dashboard on success.

### 📊 Dashboard Page
- Real-time **network status**
- Displays **active threats**
- Quick overview of connected **IoT devices**
- Navigation entry points to full scans

### 🧪 Scan Page
- Performs **ARP spoofing detection**
- Performs **DNS spoofing detection**
- Shows **detailed scan results** and prevention suggestions

### 📡 IoT Devices Page
- Lists all detected IoT devices on the network
- View each device's:
  - IP and MAC address
  - Open ports
  - Known vulnerabilities
- Buttons to **port scan** and **vulnerability scan** per device

### 📄 Report Page
- Displays a list of **previous scan reports**
- Options to **share** or **delete** reports
- Tap a report to view its **details**

### ⚙️ Settings Page
- View account name and email
- **Logout** from Firebase
- Enable/disable:
  - Notifications
  - Threat alerts
  - Vulnerability alerts
  - Cloud sync
- Choose scan frequency: Hourly, Daily, Weekly, Manual
- View app version, Terms of Service, and Privacy Policy

---

## 🧑‍💻 Tech Stack

- **Frontend**: Kotlin, Android SDK, XML, Material Design 3
- **Architecture**: MVVM with LiveData & ViewModel
- **Backend**: Firebase Authentication, Firebase Firestore (for cloud sync)
- **Networking**: Java Socket API, ARP/DNS table monitoring
- **Tools**: Android Studio, Gradle (Kotlin DSL), GitHub

---

## 📌 Scope and Limitations

### ✅ Scope
- Detects ARP and DNS spoofing attacks
- Identifies IoT devices on the same LAN
- Performs port scanning on local IPs
- Scans for known vulnerabilities based on open ports
- Allows cloud sync of reports via Firebase

### ⚠️ Limitations
- Scans work only **within the same local network** (e.g., Wi-Fi, hotspot)
- Does **not scan across subnets or external IPs**
- **Cloud sync** may require stable internet access
- **Battery-intensive** during deep scanning
- Vulnerability detection is **based on known patterns**, not exhaustive CVE scanning

---

## 🔒 Privacy and Security

- User authentication via **Google Sign-In**
- Reports and logs stored **locally by default**
- Cloud sync is **optional** and user-controlled
- No sensitive data is transmitted without user consent

---

## 📤 Deployment Notes

- Test using **mobile hotspot** to ensure all devices are on the same subnet.
- For GitHub deployment, push both the Android Studio project and APK to the repository.

---

## 📞 Support

If you encounter issues, open an [Issue](https://github.com/yourusername/yourrepo/issues) or contact the development team directly.

---

© 2025 CyberSec Segurista Team. All rights reserved.
