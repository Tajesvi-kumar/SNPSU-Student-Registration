# 🌌 Sapthagiri NPS University // Student Registration Portal

Welcome to the **Sapthagiri NPS University Student Registration & Access Portal**. This application is a fully-featured, front-end web portal designed with a premium, high-fidelity **Zero-Gravity Space and Formal Gold** aesthetic. 

The portal serves as a formal student registration system integrated with a Firebase Firestore database, enabling students to enroll, request admissions credentials, generate cryptographic holographic travel/admissions passes, and allow university administrators to review registrations.

---

## ✨ Features

- **💫 Zero-Gravity Space Backdrop**: An immersive, drifting space and nebula background with clean custom-designed visual layers.
- **🛡️ Glassmorphic Design Aesthetics**: Advanced CSS variables supporting smooth hover states, custom glass panels, and golden letterhead accents.
- **🧬 Dynamic Cyber-Input Fields**: Visual interactive fields that "levitate" on focus, featuring validation shake animations and glowing hazard error indicators.
- **🛰️ Biometric Scanner Integration**: Photo upload zone that displays a dynamic glowing cyan scanner laser animation during upload.
- **💳 Holographic Admission Pass**: Generates a flat, weightless holographic travel/admission ID card upon registration or verification.
- **📄 PDF Export Utility**: Integrated `html2pdf.js` framework enabling students to download their digital admission pass as a local PDF document.
- **📦 Firebase Integration**: Full data persistence layer utilizing Firebase Firestore for secure, real-time database transactions.

---

## 🛠️ Technology Stack

- **Markup & Structure**: Modern semantic HTML5
- **Design & Styling**: Pure Vanilla CSS3 with premium design tokens (using custom fonts *Playfair Display*, *Source Sans 3*, and *Orbitron*)
- **Logic & Animations**: Dynamic Vanilla ES6 JavaScript (animations powered by CSS keyframes and vanilla event listeners)
- **Icons**: Lucide Icons CDN
- **Database Backend**: Firebase SDK v8 (Firestore Cloud Storage)
- **PDF Generation**: html2pdf.js library

---

## 📂 Project Structure

```text
student-reg/
├── index.html           # Main admission and registration form
├── login.html           # Portal access gateway for students and administrators
├── dashboard.html       # Administrator review dashboard
├── firebase-config.js   # Firebase Firestore connectivity credentials
├── logo.png             # Sapthagiri NPS University Official Emblem
└── .gitignore           # Standard git exclusion file
```

---

## 🚀 Getting Started

### Prerequisites

You need a web server or a package runner (like Node.js or Python) to run the portal locally and enable file modules/CORS headers.

### Running Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Tajesvi-kumar/SNPSU-Student-Registration.git
   cd SNPSU-Student-Registration
   ```

2. **Serve the files**:
   - **Using Node.js (Recommended)**:
     ```bash
     npx http-server -p 3000
     ```
   - **Using Python**:
     ```bash
     python -m http.server 3000
     ```

3. **Access the application**:
   - Registration Portal: `http://localhost:3000/index.html`
   - Access & Pass Gateway: `http://localhost:3000/login.html`
   - Admin Dashboard: `http://localhost:3000/dashboard.html`

---

## 🔒 Configuration

Firebase settings can be configured inside **`firebase-config.js`**. The portal is pre-configured with active database credentials. To use a different Firestore instance, update the `firebaseConfig` object:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  databaseURL: "YOUR_DATABASE_URL",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID",
  measurementId: "YOUR_MEASUREMENT_ID"
};
```

---

## 🏛️ License & Copyright

Sapthagiri NPS University Admissions © 2025-2026. All rights reserved. Built with passion and zero-gravity precision.
