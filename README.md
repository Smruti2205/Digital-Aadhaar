# Digital-Aadhaar
### Cybersecurity Awareness & Digital Safety Platform

> Digital-Aadhaar is an interactive cybersecurity awareness and digital safety platform designed to help users identify and prevent online scams, phishing attempts, QR frauds, deepfakes, and other cyber threats through practical simulations and guided learning.

> The platform provides a safe environment where users can explore real-world digital risks, improve cybersecurity awareness, and practice secure online behavior.


---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Modules](#modules)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Future Scope](#future-scope)
- [License](#license)

---

## Overview

**Digital Aadhaar** is a cybersecurity awareness mobile application built for the Indian digital ecosystem. It empowers users — especially those new to digital services — to safely practice real-world digital tasks like UPI payments, Aadhaar usage, and government scheme navigation while learning to identify phishing attempts, deepfakes, QR fraud, and AI-powered scams.

The platform is built using **Ionic + React + TypeScript**, backed by **Firebase** for authentication and real-time data, and includes an **Express.js** backend for AI-powered scam simulation.

---

## Features

| Feature | Description |
|---|---|
| AI Scam Chat Simulation | Interact with simulated scammers powered by AI to learn how to identify and respond to threats |
| QR Fraud Detection | Scan and analyze QR codes to detect malicious or fraudulent links |
| Community Siren | Report and view community-submitted scam alerts in real time |
| Learn Module | Structured lessons on cybersecurity topics relevant to Indian users |
| Quiz Module | Test your knowledge with interactive quizzes |
| Progress Tracker | Track your learning milestones and gamified achievements |
| Govt Scheme Navigator | Safely practice navigating and applying for government schemes |
| UPI Training | Simulate UPI payment flows to learn safe digital transactions |
| Emergency Module | Quick access to emergency cyber helplines and resources |
| Multilingual Support | Content available in multiple Indian languages |
| Voice-Guided Accessibility | Audio support for users with limited literacy |

---

## Modules

### 1. Dashboard
Central hub for navigating all modules. Displays user progress and recent activity.

### 2. Learn
Bite-sized cybersecurity lessons tailored for Indian digital users covering topics like safe Aadhaar usage, OTP safety, phishing awareness, and more.

### 3. Quiz
Interactive quizzes after each lesson to reinforce knowledge with gamified scoring.

### 4. Scam Simulator (AI Scam Chat)
Simulated scam conversations powered by AI. Users practice identifying and responding to live-style social engineering attacks — safely.

### 5. Scam Detector
Analyze suspicious messages, links, or content to check for scam indicators using AI-backed detection.

### 6. QR Scanner
Scan QR codes and get an instant safety assessment to prevent QR-based fraud.

### 7. UPI Training
Step-by-step walkthroughs of UPI payment flows to build confidence and safety habits.

### 8. Government Scheme Navigator
Browse, learn about, and practice navigating real government schemes (e.g., PM Jan Dhan, Aadhaar-linked services) in a sandbox environment.

### 9. Community Siren
A community-driven alert board where users can report and view real-time scam warnings from their region.

### 10. Progress Tracker
Visual dashboard of completed lessons, quiz scores, and earned badges.

### 11. Emergency
One-tap access to national cybercrime helplines and emergency contacts.

---

## Tech Stack

### Frontend
- Ionic React
- TypeScript
- React Router
- CSS

### Backend
- Node.js
- Express.js

### Database & Services
- Firebase Authentication
- Firebase Realtime Services

### Tools & Testing
- Vite
- Cypress
- ESLint
- Capacitor

---

## Project Structure

```
Digital-Aadhaar/
├── public/
│   └── assets/              # App images and icons
├── src/
│   ├── pages/               # All app screens
│   │   ├── Dashboard.tsx
│   │   ├── Learn.tsx
│   │   ├── Quiz.tsx
│   │   ├── ScamSimulator.tsx
│   │   ├── ScamDetector.tsx
│   │   ├── QRScanner.tsx
│   │   ├── UPITraining.tsx
│   │   ├── GovtCategories.tsx
│   │   ├── SchemeList.tsx
│   │   ├── SchemeDetail.tsx
│   │   ├── SchemePractice.tsx
│   │   ├── SchemeSuccess.tsx
│   │   ├── CommunitySiren.tsx
│   │   ├── Progress.tsx
│   │   ├── Emergency.tsx
│   │   ├── Login.tsx
│   │   └── Register.tsx
│   ├── context/             # Global state (App, User, Language, History)
│   ├── services/            # AI, QR, siren, and translation services
│   ├── backend/             # Express.js server
│   ├── firebase.tsx         # Firebase config & init
│   └── App.tsx              # Root component + routing
├── cypress/                 # E2E tests
├── capacitor.config.ts      # Capacitor mobile config
├── vite.config.ts           # Vite build config
└── package.json
```

---

## Future Scope

- **Voice Scam Detection** – Identify scam patterns in audio/phone calls
- **Deepfake Detection** – ML-powered video analysis
- **Government Platform Integration** – Direct links to DigiLocker, UMANG, and other official portals
- **Nationwide Scam Alert Network** – Federated, region-specific scam alert broadcasting
- **Expanded Language Support** – More regional Indian languages

---

## License

This project is licensed under the **MIT License**.

---
