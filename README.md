# List of **local-first, privacy-focused apps that work entirely offline.**

![Beta](https://img.shields.io/badge/Status-Beta-orange)

---

### 📝 Planndu: *Decentralized Task Management*
> An offline-first, peer-to-peer task manager that syncs across your devices without a central server.
 
**[planndu.com](https://planndu.com)** 

[![Available on App Store](https://img.shields.io/badge/App%20Store-Available-blue?logo=apple)](https://apps.apple.com/us/app/planndu-tasks-notes-focus/id6754592039)
[![Available on Google Play](https://img.shields.io/badge/Google%20Play-Available-green?logo=google-play)](https://play.google.com/store/apps/details?id=com.leadstepp.alldone)
 
Planndu is built on the premise that your tasks belong to you, not a cloud provider. Devices discover and sync with each other directly over local networks using P2P protocols. Your data never leaves your control. Built for people who are serious about privacy and serious about productivity.
 
| Detail | Info |
| :--- | :--- |
| **Stack** | Kotlin Multiplatform · Ktor · WebSockets |
| **Sync** | Local Service Discovery · P2P (no central server) |
| **Database** | SQLDelight (fully local) |
| **Status** | Active Development · Beta Access Available |
| **Focus** | Decentralized · End-to-end local · Zero cloud dependency |
 
> 💡 Visit [planndu.com](https://planndu.com) to learn more.
 
---

### 📱 PomPom: *Motion-Controlled Productivity*
> A sleek focus timer that uses device motion to keep you accountable.
 
**[pompomapp.cc](https://pompomapp.cc)**

[![Available on App Store](https://img.shields.io/badge/App%20Store-Available-blue?logo=apple)](https://play.google.com/store/apps/details?id=com.pompom.pomodoro.focus.timer)
[![Available on Google Play](https://img.shields.io/badge/Google%20Play-Available-green?logo=google-play)](https://apps.apple.com/us/app/pompom-pomodoro-focus-timer/id6761312217)
 
PomPom reimagines the Pomodoro technique by using your phone's gyroscope and accelerometer to control your focus timer mid-session keeping you in flow. Built with Kotlin Multiplatform and Compose Multiplatform for a truly native feel on both iOS and Android from a single shared codebase.
 
| Detail | Info |
| :--- | :--- |
| **Stack** | Kotlin Multiplatform · Compose Multiplatform |
| **Platforms** | iOS · Android |
| **Status** | ✅ Live on App Store & Google Play |
| **Focus** | Offline-first · No account required · No data collected |
 
---

### 🔐 VaultNote: *Encrypted Local Journal*
> A private, offline-first journaling app. Your entries never leave your device.
 
![Concept](https://img.shields.io/badge/Status-In%20Development-purple)
 
VaultNote is a distraction-free writing space for thoughts you actually want to keep private. Everything is encrypted at rest using device-local keys, there's no server, no sync, no account. Open it, write, close it. Your words stay yours. Designed for daily journaling, meeting notes, or anything you'd rather not trust to a cloud provider.
 
| Detail | Info |
| :--- | :--- |
| **Stack** | Kotlin Multiplatform · Compose Multiplatform · SQLDelight |
| **Platforms** | iOS · Android · Desktop |
| **Status** | 🔨 In Development |
| **Focus** | AES-256 encryption at rest · Zero network access · No accounts |
 
---
 
### 📡 NearShare: *Local File Transfer*
> Drag-and-drop file sharing across devices on the same network, no internet required.
 
![Concept](https://img.shields.io/badge/Status-Early%20Alpha-red)
 
NearShare makes moving files between your own devices as simple as it should be. Devices on the same Wi-Fi network discover each other automatically via mDNS, and transfers happen directly, no cloud relay, no upload/download, no size limits. Think AirDrop but cross-platform and fully open.
 
| Detail | Info |
| :--- | :--- |
| **Stack** | Kotlin Multiplatform · Ktor · Local Service Discovery (mDNS) |
| **Platforms** | iOS · Android · Desktop |
| **Status** | 🧪 Early Alpha |
| **Focus** | LAN-only transfer · No size limits · No cloud relay |
 
---
 
### 🗓️ Offline Cal: *Calendar That Works Anywhere*
> A fully offline calendar with optional P2P sync between your own devices.
 
![Concept](https://img.shields.io/badge/Status-Planned-lightgrey)
 
Most calendar apps are just thin clients for a remote server, open them offline and they're useless. Offline Cal stores everything locally first and optionally syncs across your devices peer-to-peer, with no third-party server in the chain. Supports iCal import/export for compatibility with existing workflows.
 
| Detail | Info |
| :--- | :--- |
| **Stack** | Kotlin Multiplatform · Compose Multiplatform · SQLDelight · WebSockets |
| **Platforms** | iOS · Android |
| **Status** | 📋 Planned |
| **Focus** | Offline-first · iCal compatible · Optional P2P sync |
 
---

## 🛠️ Toolbox

| Category | Technologies |
| :--- | :--- |
| **Cross-Platform** | Kotlin Multiplatform, Compose Multiplatform |
| **Backend/P2P** | Ktor, WebSockets, Local Service Discovery |
| **Databases** | SQLDelight (or your preferred local DB) |

---

## 🧭 Philosophy
 
> *"The best privacy tool is one that doesn't need to ask for your trust, because it was never designed to take your data in the first place."*
 
Local-first isn't just an architecture pattern. It's a statement about who software is built for. Every product in this list is designed to work completely without an internet connection, give users full ownership of their data, and degrade gracefully when connectivity is limited or unavailable.
 
If that resonates with you as a user, a fellow developer, or a potential collaborator, I'd love to hear from you.

📧 **Email** [boberzhabka@gmail.com](mailto:boberzhabka@gmail.com)
 
---
 
<div align="center">
  <sub>Built with passion and a deep respect for user privacy.</sub>
</div>
