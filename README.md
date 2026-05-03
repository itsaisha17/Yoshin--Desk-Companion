<p align="center">
  <img src="https://your-image-url.com/yoshin-logo.png" alt="Yoshin Logo" width="200">
</p>

---


# 🧠 Yoshin: Desk Companion

**Yoshin** is an IoT-based productivity and focus assistant, designed to improve **daily efficiency**, **task completion**, and **habit building** with constant tracking of behaviour patter recognisation ,using machine learning classfiers. Combined with a modern **React Native mobile app**, Yoshin offers real-time facial recognition, task monitoring, energy and mood tracking, and smart AI-driven recommendations.

---

## 🚀 What is Yoshin?

Yoshin: Desk Companion is a smart IoT productivity model that **monitors your presence and focus using OpenCV**, sends alerts when distractions occur, and integrates with a mobile app for task tracking, energy analysis, and more.

Perfect for:
- 🚀 **Productivity hackers**
- 🎓 **Students**
- 👨‍👩‍👧 **Parents wanting to monitor study time**
- 🧑‍💼 **Remote workers**

---

## 🔍 Key Features 

### 📸 Focus Monitoring (IoT)
- Uses **OpenCV** to detect:
  - If you're **focused**, **idle**, or **distracted**
  - Whether you're **in frame**
- Sends alerts if you're away for over **15 minutes** (default)
- Great for **task accountability** and **parental monitoring**

### 🤖 AI Task Bot (Premium Add-on)
- Uses **sleep data** and **screen time** to:
  - Analyze productivity trends
  - Suggest optimal working hours
  - Boost productivity by **2×** with smart recommendations

---
## ⚒ Working 
```
👨 You (in front of webcam)
      ↓
🎥 Laptop Webcam
      ↓
🤖 Features extracted (face_detected, head_tilt_angle, shoulder_position)
      ↓
🧠 Model (RandomForestClassifier) → Predicts: Working / Distracted / Idle
      ↓
📡 Send prediction to Raspberry Pi over socket
      ↓
🖥️ Raspberry Pi OLED shows reaction (emoji + time)
```
---
## 📱 Mobile App Features
<img align="left" width="400" height="800" alt="image" src="https://github.com/user-attachments/assets/c4c6357f-b248-4116-8e0d-c5bfdb6a93da" /><img width="400" height="800" alt="image" src="https://github.com/user-attachments/assets/0e2f8c04-3a0a-431c-950a-5e23443198dd" />



### 🗓️ Today’s Schedule
- Add and manage tasks with real-time toggling (open/upcoming)
- Clean, dark-themed UI for minimal distractions
- FAQ access for productivity guidance

### ⚡ Energy Monitoring
- Track daily and weekly energy patterns
- Interactive line charts for insights
- AI-based suggestions for improving energy use

### 🤝 Collaborative Challenges
- Team-based goal setting and performance tracking
- Share achievements and monitor group productivity

### 😊 Mood Tracking
- Daily mood logging with visual history
- Pattern detection for emotional trends
- Recommendations tailored to mood

---

## 🛠️ Technology Stack

### IoT Companion
- **OpenCV** for face detection and activity recognition
- **Python** + **microcontroller integration** for alerting system
- **Raspberry Pi**

### Mobile App
- **React Native** `v0.76.9`
- **Expo Framework** `v52.0.43`
- **React Navigation** for screen routing
- **Chart Kit** for visual data analytics
- **React Spring Native** for smooth animations
- **Custom UI Styling** using StyleSheet

---

## ⚙️ Getting Started

### ✅ Prerequisites
- Node.js `v16+`
- npm or yarn
- Expo CLI
- (Optional) Python + OpenCV installed for IoT module

### 📲 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/productivity-app.git
```

2. Navigate into the project:
```bash
cd productivity-app
```

3. Install dependencies:
```bash
npm install
```

4. Run the app:
```bash
npm start         # Start development server
npm run android   # Run on Android
npm run ios       # Run on iOS
npm run web       # Run on Web
```

---

## 🧠 Core Modules

### ✅ Task Management
- Add/track daily tasks
- Toggle between open and upcoming
- Dark UI and priority-based organization

### ⚡ Energy Analytics
- Weekly energy tracking via visual charts
- Custom metrics
- AI suggestions to optimize performance

### 🤝 Collaboration
- Track team goals and progress
- Share achievements and view performance insights

### 🧠 Smart Behavior Monitoring (IoT)
- Real-time facial recognition with OpenCV
- Sends alerts after 15+ mins of absence
- Passive, non-intrusive focus tracking

---

## 🤝 Contributing

We welcome community contributions!

1. Fork the repository  
2. Create your feature branch:  
```bash
git checkout -b feature/AmazingFeature
```
3. Commit your changes:  
```bash
git commit -m "Add AmazingFeature"
```
4. Push to your branch:  
```bash
git push origin feature/AmazingFeature
```
5. Open a Pull Request

---

## 📄 License

Licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for more details.

---

## 📬 Contact

**Project Repository**:https://github.com/vaishnavi14705/task-bot.git




