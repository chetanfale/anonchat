# AnonChat

AnonChat is a secure, real-time web application for creating private chatrooms with a hacker/terminal aesthetic. It prioritizes **privacy and access control**.

## 🚀 Features
- Real-time messaging with Firebase Firestore
- Password-protected room creation
- Approval-based access control
- **Unique Privacy**: No chat history until `/getbac` is used
- Online/offline status
- Admin commands:
  - `/getid` → List members
  - `/getadmin` → Grant admin role
  - `/killhouse` → Clear and regenerate room
- Hacker-inspired UI

## 🛠 Tech Stack
- Frontend: HTML + Tailwind CSS + JS
- Backend: Firebase (Auth + Firestore)

## ⚡ Setup
1. Clone repo  
   ```bash
   git clone https://github.com/chetanfale/anonchat.git
   cd anonchat
2. Setup Firebase project → enable Firestore + Anonymous Auth
3. Paste your Firebase config in index.html
4. Deploy:
   ```bash
   npm install -g firebase-tools
   firebase login
   firebase init
   firebase deploy
