<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>
# SlotIn 🚀 — The Last-Minute Life Saver

SlotIn is a high-octane, crisis-driven productivity companion that transforms passive task lists into an interactive, AI-optimized battle station. Built with a responsive, high-contrast visual design, SlotIn bridges the gap between external commitments and focused execution.

🌐 **Live Deployed Application:** [https://the-last-minute-life-saver-210361250649.asia-southeast1.run.app]

---

## 📋 Table of Contents
- [Problem Statement Selected](#-problem-statement-selected)
- [Solution Overview](#-solution-overview)
- [Key Features](#-key-features)
- [Technologies Used](#-technologies-used)
- [Google Technologies Utilized](#-google-technologies-utilized)
- [Local Development Setup](#-local-development-setup)

---

## 🔍 Problem Statement Selected
In fast-paced academic and professional environments, users face severe "deadline paralysis." Standard calendar apps and passive to-do lists fail to motivate immediate action, causing critical tasks to slip through the cracks. Students and professionals need more than a static timeline; they require a dynamic workspace companion that actively minimizes friction, surfaces urgent commitments, and instantly transforms passive schedules into highly focused execution blocks.

## 💡 Solution Overview
**SlotIn** turns procrastination into focused momentum. By directly connecting to a user's communication hubs, SlotIn uses generative AI to instantly analyze incoming assignments and high-urgency notifications. It then programmatically restructures the user's day into optimized work "slots," providing an aggressive, high-contrast dashboard that acts as an emergency mission control center for beating deadlines.

## ✨ Key Features
* **🔄 Real-Time Course Assignment Sync:** Directly pulls active assignments, materials, and due dates to populate your workspace automatically without manual entries.
* **📧 High-Urgency Email Scanning:** Scans incoming communications contextually to extract urgent updates, ensuring nothing slips through the cracks.
* **🧠 AI-Optimized Task Allocation:** Intelligently maps out day schedules based on task weight and urgency parameters using generative intelligence.
* **🔒 Secure Persistence & Auth:** Secure synchronization of tasks, completed milestones, habit streaks, and user-profile settings across sessions.
* **🎮 "Battle Station" Dashboard UX:** A responsive, dark, high-contrast UI tailored specifically to eliminate visual clutter and induce flow-state concentration during crunch periods.

## 🛠️ Technologies Used
* **Frontend & Animation:** React, TypeScript, Tailwind CSS, Vite, Lucide React (Icons), Motion/React
* **Backend Server:** Node.js, Express Framework
* **Database & States:** Firebase Cloud Firestore

## ☁️ Google Technologies Utilized
* **Google AI Studio & Gemini 3.5 Flash:** Powers the core intelligence engine responsible for parsing urgency indicators, extracting implicit milestones, and optimizing daily schedule matrices.
* **Google Cloud Run:** Hosts the live, production-grade application container on an auto-scaling serverless layer.
* **Google Classroom API:** Automates data synchronization of active coursework datasets.
* **Gmail API:** Facilitates automated analysis of incoming critical communications.
* **Firebase Cloud Firestore:** Functions as the real-time NoSQL storage tier handling authorization boundaries and active states.

---

## 💻 Local Development Setup

To run this project locally, clone the repository and install dependencies:

```bash
# Clone the repository
git clone [https://github.com/Chetan173205/SlotIn-the-last-minute-life-saver-.git](https://github.com/Chetan173205/SlotIn-the-last-minute-life-saver-.git)

# Navigate into the project folder
cd SlotIn-the-last-minute-life-saver-

# Install the dependencies
npm install

# Start the local development server
npm run dev
