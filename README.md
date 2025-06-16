# CTAPDEVL_PROJECT_COM223

# 📱 Network Spoofing Detection and Prevention of IoT Devices with Vulnerability Analysis

An Android-based mobile application designed to **detect and prevent ARP and DNS spoofing attacks**, **scan IoT devices** for open ports and vulnerabilities, and **generate security reports** — built using MVVM architecture.

---

## 🧭 User Manual

This section guides the end-user in using the **Network Spoofing Detection and Prevention of IoT Devices with Vulnerability Analysis** app.

---

### 🔐 1. Logging In

**Steps:**
1. Launch the app.
2. On the Login screen, tap **“Sign in with Google”**.
3. Choose your Google account to proceed.

**Possible Scenarios:**
- ✅ *Success:* User is redirected to the **Dashboard**.
- ❌ *Failure:* No internet connection → shows a **toast error**.
- ❌ *Canceled:* User backs out of sign-in → remains on login screen.

---

### 📊 2. Viewing Dashboard

**Steps:**
1. After login, the **Dashboard** loads.
2. View:
   - Network status summary
   - Active threats
   - Connected IoT devices

**Scenarios:**
- ✅ *Secure Network:* Shows status as "Secure".
- ⚠️ *Threat Detected:* Status turns **orange** or **red**, and threat appears in list.

**Icons Used:**
- 🛡️ = Secure
- ⚠️ = Suspicious activity
- 🔴 = Confirmed threat

---

### 🧪 3. Running a Network Scan

**Steps:**
1. Go to the **Scan** tab from the bottom navigation.
2. Tap **“Start Scan”**.
3. The app performs:
   - ARP spoofing check
   - DNS spoofing analysis
4. Results display below with details.

**Scenarios:**
- ✅ *No Threats:* Scan completes with **“No spoofing detected.”**
- ⚠️ *ARP Spoofing Found:* Warning shown with MAC/IP mismatch.
- ⚠️ *DNS Spoofing Found:* DNS server entries do not match expected ones.

**Icons/Symbols:**
- ✅ = Safe
- ⚠️ = Warning
- ❌ = Critical issue

---

### 📡 4. Viewing IoT Devices

**Steps:**
1. Go to the **Devices** tab.
2. All devices on the same network will appear.
3. Tap **“View Details”** on any device.

**Features:**
- View IP, MAC, Manufacturer
- Tap buttons for:
  - **Port Scan**
  - **Vulnerability Scan**

**Scenarios:**
- ✅ *Device Online:* All data retrieved.
- ❌ *Device Offline:* Message shown: "Unreachable device."

---

### 📄 5. Viewing Reports

**Steps:**
1. Go to the **Reports** tab.
2. Tap on any item to view:
   - Scan metadata
   - Threat/vulnerability results
   - Affected devices

**Other Actions:**
- Share or delete a report

**Symbols:**
- 📄 = Report item
- 📤 = Share
- 🗑️ = Delete

---

### ⚙️ 6. Configuring Settings

**Steps:**
1. Go to the **Settings** tab.
2. View and modify:
   - Account info
   - Logout button
   - Notification toggles
   - Scan frequency (radio buttons)
   - Cloud sync toggle

**Symbols/Controls:**
- 🔔 Notifications → toggle switch
- ☁️ Cloud sync → toggle switch
- ⏱️ Scan frequency → radio buttons (Hourly, Daily, etc.)

---

### 📃 7. Understanding the Icons

| Icon / Symbol | Meaning |
|---------------|---------|
| 🛡️ | Secure status |
| ⚠️ | Warning/Threat detected |
| ❌ | Critical issue (e.g., spoofing confirmed) |
| 📄 | Saved scan report |
| 📤 | Share report |
| 🗑️ | Delete report |
| 🔔 | Notification settings |
| ☁️ | Cloud Sync enabled |

---

### ℹ️ Notes

- Connect all devices (phone, IoT) to the **same hotspot network** to scan them.
- Make sure location permission is granted for Wi-Fi scans to work.

---

© 2025 CyberSec Segurista Team. All rights reserved.
