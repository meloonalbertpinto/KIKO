# KIKO
🧸 KIKO  An AI-powered IoT companion &amp; mobile ecosystem that replaces screen addiction with interactive storytelling, emotion-aware conversations, and parental empowerment for children aged 6–15.

# 🧸 KIKO — The Digital Grandparent
### *Reclaiming Childhood Through Intelligent Companionship*

<p align="center">
  <img src="assets/kiko-banner.png" alt="KIKO Banner" width="800"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-In%20Development-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Platform-IoT%20%2B%20Mobile-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AI-Emotion%20Aware-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
</p>

<p align="center">
  <b>🎯 Replacing the Dopamine Hit of Screens with the Oxytocin Comfort of Storytelling</b>
</p>

---

## 📖 Table of Contents

- [🌟 What is KIKO?](#-what-is-kiko)
- [❗ The Problem](#-the-problem)
- [💡 Our Solution](#-our-solution)
- [🏗️ System Architecture](#️-system-architecture)
- [🛠️ Technology Stack](#️-technology-stack)
- [🔧 Hardware Components](#-hardware-components)
- [📱 App Features](#-app-features)
- [🎯 Key Objectives](#-key-objectives)
- [📂 Project Structure](#-project-structure)
- [🚀 Getting Started](#-getting-started)
- [🔒 Privacy & Security](#-privacy--security)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)
- [👥 Team](#-team)

---

## 🌟 What is KIKO?

> *"Every child deserves a story, not a screen."*

**KIKO** is a hybrid socio-technical ecosystem designed to bridge the
**Grandparent Vacuum** in modern nuclear families. It combines an
**IoT-enabled smart companion device** with a **dedicated mobile application**
to nurture children aged **6–15** through:

🗣️ **Interactive Storytelling** — AI-driven, culturally resonant narratives
🧠 **Emotion-Aware Conversations** — Real-time voice sentiment analysis
🌍 **Multilingual Support** — Regional mother tongues + English
👨‍👩‍👧 **Parental Empowerment** — Behavioral insights, health tracking & community

┌─────────────────────────────────────────────┐
│                                             │
│       👴 Grandparent's Wisdom               │
│                  +                          │
│       🤖 Artificial Intelligence            │
│                  =                          │
│       🧸 KIKO — The Digital Grandparent     │
│                                             │
└─────────────────────────────────────────────┘
---

## ❗ The Problem

<p align="center">
  <img src="assets/problem-statement.png" alt="Problem" width="600"/>
</p>

Modern nuclear families face a **silent crisis**:

| 😟 Problem | 💥 Impact |
|---|---|
| 👴 **Grandparent Vacuum** | No multi-generational emotional support |
| 📱 **Digital Pacifier Culture** | Parents use screens to suppress tantrums |
| 🧪 **Dopamine Dependency Loop** | Children become addicted to instant gratification |
| 👁️ **Physiological Damage** | Eye strain, sleep disruption, sedentary risks |
| 🧠 **Developmental Setbacks** | Impaired creativity, stubbornness, can't self-soothe |
| 😔 **Parental Isolation** | No mentorship, no community, no guidance |



```
**THE VICIOUS CYCLE:**
                    
        😰 Stressed Parent
              │
              ▼
        📱 Hands Phone to Child
              │
              ▼
        🧒 Child Glued to Screen
              │
              ▼
        😤 Tantrum Without Phone
              │
              ▼
        😰 Back to Stressed Parent
              │
              └──────── 🔄 REPEAT ────────┘
```


> **The market either entertains without nurturing or educates without
> emotionally engaging. Nothing addresses the holistic need.**

---

## 💡 Our Solution

<p align="center">
  <img src="assets/solution-overview.png" alt="Solution" width="700"/>
</p>

**KIKO operates on a dual-layered architecture:**

### 🧒 Layer 1 — For the Child (Hardware Companion)

| Feature | Description |
|---|---|
| 🎙️ **Voice-First Interaction** | Audio-tactile engagement over visual stimulation |
| 🧠 **Emotion Detection** | Voice sentiment analysis detects mood in real-time |
| 📚 **Smart Storytelling** | AI-curated moral stories (Panchatantra, Aesop & more) |
| 🎵 **Therapeutic Audio** | Calming sounds, lullabies & ambient music |
| 🌐 **Multilingual NLP** | Responds in regional mother tongue or English |
| 🖥️ **Screen-Lite Display** | Minimal e-ink/TFT — reduces eye strain |

### 👨‍👩‍👧 Layer 2 — For the Parent (Mobile App)

| Feature | Description |
|---|---|
| 📊 **Insights Dashboard** | Behavioral trends, interest mapping & activity logs |
| 🏥 **Health Tracker** | Centralized medical records & vaccination history |
| 👥 **Digital Village** | Community platform with expert mentors & peer support |
| 🔔 **Smart Alerts** | Mood-based notifications & daily summaries |
| 🔒 **Privacy Controls** | Full parental control over data & interactions |

---

## 🏗️ System Architecture
┌──────────────────────────────────────────────────────────┐
│                      ☁️ CLOUD LAYER                      │
│  ┌─────────────┐  ┌──────────────┐  ┌────────────────┐  │
│  │  Firebase    │  │   AI/NLP     │  │   Content      │  │
│  │  Realtime DB │  │   Engine     │  │   Repository   │  │
│  │  & Auth      │  │ (Gemini API) │  │ (Stories/Audio)│  │
│  └──────┬──────┘  └──────┬───────┘  └───────┬────────┘  │
│         │                │                   │           │
└─────────┼────────────────┼───────────────────┼───────────┘
          │                │                   │
          ▼                ▼                   ▼
┌──────────────────────────────────────────────────────────┐
│                  🔗 API / MQTT LAYER                     │
│              RESTful APIs + MQTT Protocol                │
└────────────┬─────────────────────────┬───────────────────┘
             │                         │
             ▼                         ▼
┌────────────────────┐   ┌─────────────────────────┐
│   📱 MOBILE APP    │   │   🧸 IoT COMPANION      │
│                    │   │                         │
│  • React Native    │   │  • ESP32-S3             │
│  • Parent Dashboard│   │  • INMP441 Mic          │
│  • Health Tracker  │   │  • MAX98357A Speaker    │
│  • Community Forum │   │  • 1.8" TFT / E-Ink    │
│  • Notifications   │   │  • NeoPixel LED Ring    │
│                    │   │  • Li-Po Battery        │
└────────────────────┘   └─────────────────────────┘

---

## 🛠️ Technology Stack

### 📱 Mobile Application

| Technology | Purpose |
|---|---|
| ⚛️ **React Native** | Cross-platform mobile app development |
| 🔥 **Firebase** | Authentication, Realtime Database & Cloud Storage |
| 📊 **Firebase Analytics** | User behavior & engagement tracking |
| 🔔 **Firebase Cloud Messaging** | Push notifications & smart alerts |
| 🎨 **React Native Paper** | Material Design UI components |
| 📈 **Victory Charts** | Behavioral trend visualizations |
| 🗺️ **React Navigation** | In-app screen navigation |

### 🤖 AI & NLP Engine

| Technology | Purpose |
|---|---|
| 🧠 **Google Gemini API** | Conversational AI & story generation |
| 🗣️ **Google Cloud Speech-to-Text** | Voice recognition & transcription |
| 🔊 **Google Cloud Text-to-Speech** | Multilingual voice synthesis |
| 💬 **Dialogflow CX** | Intent detection & conversation flow |
| 😊 **TensorFlow Lite** | On-device emotion classification |
| 🌐 **Google Translate API** | Real-time multilingual support |

### 🔧 IoT & Embedded Systems

| Technology | Purpose |
|---|---|
| 🛠️ **Arduino IDE** | Firmware development environment |
| 📡 **ESP-IDF Framework** | ESP32-S3 development framework |
| 🔌 **MQTT Protocol** | Lightweight IoT communication |
| 🌐 **WiFi (ESP32 Built-in)** | Cloud connectivity |
| 🔋 **FreeRTOS** | Real-time task management on ESP32 |

### ☁️ Backend & Database

| Technology | Purpose |
|---|---|
| 🔥 **Firebase Firestore** | NoSQL database for user data & logs |
| 🔐 **Firebase Auth** | Secure user authentication (OAuth2) |
| 📦 **Firebase Cloud Storage** | Audio files & media content storage |
| ⚡ **Firebase Cloud Functions** | Serverless backend logic |
| 🔑 **Firebase Security Rules** | Data access control & encryption |

### 🛡️ Security & Privacy

| Technology | Purpose |
|---|---|
| 🔐 **AES-256 Encryption** | End-to-end data encryption |
| 🧠 **Edge AI (TFLite)** | On-device processing — no cloud dependency |
| 👶 **COPPA Compliance** | Child data protection standards |
| 🔑 **JWT Tokens** | Secure API authentication |

---

## 🔧 Hardware Components

### 🧸 KIKO Companion Device — Bill of Materials

| # | Component | Model | Purpose | Qty |
|---|---|---|---|---|
| 1 | 🧠 Microcontroller | **ESP32-S3 WROOM** | Main processing unit with WiFi + BLE | 1 |
| 2 | 🎙️ Microphone | **INMP441 (I2S)** | High-fidelity voice capture | 1 |
| 3 | 🔊 Amplifier + Speaker | **MAX98357A (I2S)** | Audio output for stories & responses | 1 |
| 4 | 🖥️ Display | **1.8" ST7735 TFT / E-Ink** | Minimal visual feedback (expressions) | 1 |
| 5 | 💡 LED Ring | **NeoPixel WS2812B (12-bit)** | Mood indication via color patterns | 1 |
| 6 | 🔋 Battery | **3.7V Li-Po 2000mAh** | Portable power supply | 1 |
| 7 | ⚡ Charging Module | **TP4056 USB-C** | Battery charging & protection | 1 |
| 8 | 🔘 Buttons | **Tactile Push Buttons** | Power, volume, interaction triggers | 3 |
| 9 | 📦 Enclosure | **3D Printed / Silicone Shell** | Child-safe, soft-touch body | 1 |

### 📌 Pin Configuration (ESP32-S3)
ESP32-S3 WROOM Pin Map:

┌──────────────────────────────────────┐
│ INMP441 Microphone (I2S Input) │
│ SCK → GPIO 14 │
│ WS → GPIO 15 │
│ SD → GPIO 32 │
│ │
│ MAX98357A Speaker (I2S Output) │
│ BCLK → GPIO 26 │
│ LRC → GPIO 25 │
│ DIN → GPIO 22 │
│ │
│ ST7735 TFT Display (SPI) │
│ SCL → GPIO 18 │
│ SDA → GPIO 23 │
│ CS → GPIO 5 │
│ DC → GPIO 2 │
│ RST → GPIO 4 │
│ │
│ NeoPixel LED Ring │
│ DIN → GPIO 13 │
│ │
│ Buttons │
│ Power → GPIO 34 │
│ Volume+ → GPIO 35 │
│ Action → GPIO 36 │
└──────────────────────────────────────┘


---

## 📱 App Features

### 🏠 Home Dashboard
> Quick overview of child's daily activity, mood summary & alerts

### 📊 Behavioral Insights
> Weekly/monthly trend reports — interests, engagement patterns & growth indicators

### 🏥 Health & Medical Tracker
> Vaccination records, medical history, growth milestones & doctor visit logs

### 👥 Digital Village (Community)
> Expert Q&A, peer parenting forums, curated articles & mentorship connections

### 🎛️ Device Control
> Manage KIKO companion — set schedules, content preferences & interaction limits

### 🔔 Smart Notifications
> Mood-based alerts, daily summaries & milestone celebrations

---

## 🎯 Key Objectives

| # | Objective | Status |
|---|---|---|
| 1 | 🧸 Build IoT-Enabled Smart Companion | 🟡 In Progress |
| 2 | 🌐 Integrate Multilingual NLP Engine | 🟡 In Progress |
| 3 | 😊 Implement Emotion-Aware AI | 🔴 Planned |
| 4 | 📊 Create Parental Insights Dashboard | 🟡 In Progress |
| 5 | 📚 Curate Value-Based Story Content | 🟡 In Progress |
| 6 | 👥 Build Digital Village Community | 🔴 Planned |
| 7 | 🏥 Develop Health & Medical Tracker | 🔴 Planned |
| 8 | 🔒 Ensure COPPA-Compliant Data Privacy | 🟡 In Progress |

---

## 📂 Project Structure
KIKO/
│
├── 📁 hardware/
│ ├── 📁 firmware/
│ │ ├── main.ino # Main Arduino sketch
│ │ ├── wifi_manager.h # WiFi connection handler
│ │ ├── audio_capture.h # INMP441 mic recording
│ │ ├── audio_playback.h # MAX98357A speaker output
│ │ ├── display_manager.h # TFT/E-Ink display control
│ │ ├── led_controller.h # NeoPixel mood lighting
│ │ ├── mqtt_client.h # MQTT communication
│ │ └── edge_ai.h # On-device TFLite inference
│ ├── 📁 schematics/
│ │ ├── circuit_diagram.png
│ │ └── pcb_layout.kicad
│ └── 📁 3d_models/
│ └── enclosure.stl
│
├── 📁 mobile-app/
│ ├── 📁 src/
│ │ ├── 📁 screens/
│ │ │ ├── HomeScreen.js
│ │ │ ├── InsightsScreen.js
│ │ │ ├── HealthTrackerScreen.js
│ │ │ ├── CommunityScreen.js
│ │ │ └── DeviceControlScreen.js
│ │ ├── 📁 components/
│ │ │ ├── MoodCard.js
│ │ │ ├── StoryPlayer.js
│ │ │ ├── TrendChart.js
│ │ │ └── AlertBanner.js
│ │ ├── 📁 services/
│ │ │ ├── firebaseConfig.js
│ │ │ ├── aiService.js
│ │ │ └── mqttService.js
│ │ ├── 📁 utils/
│ │ │ ├── encryption.js
│ │ │ └── constants.js
│ │ └── App.js
│ ├── package.json
│ └── app.json
│
├── 📁 ai-engine/
│ ├── emotion_classifier.py # Voice sentiment model
│ ├── story_generator.py # Gemini API story engine
│ ├── nlu_processor.py # Dialogflow NLU handler
│ └── tts_synthesizer.py # Text-to-Speech service
│
├── 📁 cloud-functions/
│ ├── index.js # Firebase Cloud Functions
│ ├── notifications.js # Push notification triggers
│ └── analytics.js # Data aggregation logic
│
├── 📁 assets/
│ ├── kiko-banner.png
│ ├── problem-statement.png
│ ├── solution-overview.png
│ └── architecture-diagram.png
│
├── 📁 docs/
│ ├── HARDWARE_SETUP.md
│ ├── APP_SETUP.md
│ ├── API_REFERENCE.md
│ └── PRIVACY_POLICY.md
│
├── .gitignore
├── LICENSE
└── README.md


---

## 🚀 Getting Started

### 📋 Prerequisites

```bash
# Node.js & npm
node >= 18.0.0
npm >= 9.0.0

# React Native CLI
npm install -g react-native-cli

# Arduino IDE
Arduino IDE >= 2.0
ESP32 Board Package installed

# Firebase CLI
npm install -g firebase-tools

🔧 Hardware Setup
# 1. Clone the repository
git clone https://github.com/your-username/KIKO.git
cd KIKO/hardware/firmware

# 2. Open main.ino in Arduino IDE

# 3. Select Board: ESP32-S3 Dev Module

# 4. Install required libraries:
#    - WiFi.h
#    - ArduinoJson
#    - PubSubClient (MQTT)
#    - Adafruit_NeoPixel
#    - TFT_eSPI
#    - driver/i2s.h

# 5. Upload firmware to ESP32-S3

📱 Mobile App Setup
# 1. Navigate to mobile app directory
cd KIKO/mobile-app

# 2. Install dependencies
npm install

# 3. Configure Firebase
# Add your google-services.json (Android)
# Add your GoogleService-Info.plist (iOS)

# 4. Run the application
npx react-native run-android    # For Android
npx react-native run-ios        # For iOS

☁️ Cloud Functions Setup
# 1. Login to Firebase
firebase login

# 2. Initialize project
cd KIKO/cloud-functions
firebase init functions

# 3. Deploy
firebase deploy --only functions

🔒 Privacy & Security
"Children's data is sacred. We treat it that way."

Measure	Implementation
🔐 Encryption	AES-256 end-to-end encryption for all data
🧠 Edge AI	Voice processing happens on-device — minimal cloud exposure
👶 COPPA Compliant	Full compliance with Children's Online Privacy Protection Act
🚫 No Data Selling	Zero third-party data sharing — ever
🔑 Authentication	Firebase Auth with OAuth2 + JWT tokens
🗑️ Data Deletion	Parents can delete all child data at any time
📍 No Location Tracking	KIKO does not track or store location data

🤝 Contributing
We welcome contributions! Here's how you can help:

1. 🍴 Fork the repository
2. 🌿 Create a feature branch (git checkout -b feature/your-feature)
3. 💻 Commit your changes (git commit -m 'Add your feature')
4. 📤 Push to branch (git push origin feature/your-feature)
5. 🔄 Open a Pull Request

📜 License
This project is licensed under the MIT License — see the LICENSE file for details.

👥 Team
Name	Role
🧑‍💻 Meloon Albert Pinto	Project Lead & IoT & Embedded Systems Engineer 
🧑‍💻 Joel Pinto 	Full Stack Developer
🧑‍💻 Calwin Fernandes	Full Stack Developer
🧑‍💻 Mohan B J	Full Stack Developer

<p align="center"> <img src="assets/kiko-footer.png" alt="KIKO Footer" width="400"/> </p><p align="center"> <b>🧸 KIKO — Because Every Child Deserves a Story, Not a Screen.</b> </p><p align="center"> Made with ❤️ for the children who deserve better. </p><p align="center"> ⭐ Star this repo if you believe in reclaiming childhood! ⭐ </p> ```

