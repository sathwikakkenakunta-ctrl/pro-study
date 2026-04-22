# Student Planner Pro 📖

**Student Planner Pro** (also known as **Pro Study**) is a fully gamified, real-time productivity dashboard designed to transform the student experience. It combines deep focus tools, AI-powered assistance, and social collaboration into a sleek, modern web application.

## 🚀 Live Demo
[Insert your GitHub Pages or Vercel link here]

## ✨ Features

### 🤖 Pro AI Assistant
Integrated with **Gemini AI** to help organize messy thoughts, summarize notes, and generate study plans in real-time.

### ☁️ Live Study Rooms
Create or join real-time study rooms via Firebase. Features include:
* **Live Chat**: Communicate with study partners.
* **Shared Whiteboard**: Sync notes and formulas instantly.
* **Resource Vault**: Share and store important links.

### 🎯 Focus Flow (Pomodoro)
* **Customizable Timer**: Adjust work and break intervals.
* **Zen Mode**: Eliminate distractions with a minimalist interface.
* **Deep Focus Radio**: Built-in LoFi, Classical, and Jazz stations.

### 🏆 RPG Gamification
* **XP System**: Earn points for completing tasks, habits, and focus sessions.
* **Leveling**: Climb the ranks from "Rookie Scholar" to "Grandmaster."
* **Leaderboard**: Compete with other students globally.

### 🎮 Mini-Games Hub
Take a brain break with built-in classics:
* **2048**: Numerical puzzle.
* **Memory Match**: Emoji-based memory training.
* **Tic-Tac-Toe**: Play against an AI.
* **Speed Math**: 30-second rapid-fire math blitz.

### 🌍 Global Support
Fully localized in multiple languages:
* English, Spanish (Español), Hindi (हिन्दी), French (Français), and Telugu (తెలుగు).

## 🛠️ Tech Stack

* **Frontend**: Vanilla HTML5, CSS3 (Modern Glassmorphism UI), JavaScript (ES6+).
* **Backend/Database**: [Firebase](https://firebase.google.com/) (Authentication & Firestore).
* **AI Engine**: [Google Gemini AI](https://deepmind.google/technologies/gemini/) (via Cloudflare Workers proxy).
* **Hosting**: Compatible with Vercel, Netlify, or GitHub Pages.

## 📂 Project Structure

* `index.html`: The professional marketing landing page.
* `login.html`: Secure Firebase authentication gateway.
* `dashboard.html`: The core application and main logic.

## ⚙️ Setup & Installation

1.  **Clone the repository**:
    ```bash
    git clone https://sathwikakkenakunta-ctrl.github.io/pro-study/
    ```
2.  **Configure Firebase**:
    * Create a project at the [Firebase Console](https://console.firebase.google.com/).
    * Enable **Authentication** (Google & Email/Password) and **Cloud Firestore**.
    * Replace the `firebaseConfig` object in `login.html` and `dashboard.html` with your own API keys.
3.  **AI Integration**:
    * The app uses a Cloudflare Worker proxy for Gemini AI. Update the `WORKER_URL` in `dashboard.html` to point to your deployed worker.
4.  **Run Locally**:
    * Simply open `index.html` in your browser or use a "Live Server" extension in VS Code.

## 📄 License
Commercial Proprietary License
Copyright (c) 2026 Sathwik & Vishwas Akkenakunta. All rights reserved.
This software and its source code are being sold as a commercial asset. Upon purchase, the buyer is granted full ownership and rights to modify, deploy, and monetize the application. Unauthorized distribution or sub-licensing prior to a confirmed sale is strictly prohibited.

---
**Developed by Sathwik & Vishwas Akkenakunta**
