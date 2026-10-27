# ✈️ Trip Planner Template

A lightweight, Neo-brutalist styled travel itinerary web app built with **Tailwind CSS**, **FontAwesome**, and **Cloud Firestore**. Supports real-time multi-device synchronization for planning trips together with friends or partners!

---

## 🚀 Quick Setup Guide

### Step 1: Firebase Setup
1. Go to the [Firebase Console](https://console.firebase.google.com/) and create a new project.
2. Create a **Firestore Database**:
   - Navigate to **Firestore Database** > **Create database**.
   - Choose **Test Mode** (or ensure rules allow read/write: `allow read, write: if true;`).
3. Register a Web App:
   - Go to **Project Settings (⚙️)** > **General** > **Your apps** > Click the **Web (`</>`)** icon.
   - Copy your unique `firebaseConfig` keys.

---

### Step 2: Configure the Code
1. Clone or fork this repository.
2. Open `index.html` and replace the placeholder `firebaseConfig` object with your own Firebase credentials:
   ```javascript
   const firebaseConfig = {
       apiKey: "YOUR_API_KEY",
       authDomain: "YOUR_AUTH_DOMAIN",
       projectId: "YOUR_PROJECT_ID",
       storageBucket: "YOUR_STORAGE_BUCKET",
       messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
       appId: "YOUR_APP_ID"
   };