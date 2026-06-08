# ♟️ Wolfo Chess

A modern, dynamic, and clean web-based chess platform built using HTML5, CSS3, and JavaScript, powered by Firebase Auth and Cloud Firestore.

## 🚀 Key Features
* **Local Chess Arena:** Full chess engine supporting legal moves, castling, stalemate, check, and pawn promotion.
* **Dynamic Clocks:** Play with standard time controls (1 min Bullet, 3/5 min Blitz, or 10 min Rapid).
* **Global Theme Mode:** Seamless synchronization of Dark and Light modes across all pages using LocalStorage.
* **Interactive Guides & Quiz:** Visual boards showing how pieces move, plus a chess knowledge quiz.
* **Secret Admin Panel:** A secure interface to view and manage registered users.

---

## 🏁 How to Get Started

### 1. Run the Project
Since this project uses modern JavaScript modules for Firebase, it must be run through a local server rather than just opening the HTML file directly.
* **VS Code:** Right-click `index.html` and choose **"Open with Live Server"**.
* **Python:** Run `python -m http.server 8000` in your terminal and open `http://localhost:8000` in your browser.

### 2. Create a User Account
1. When the site loads, you will land on the login page (`index.html`).
2. Click the link at the bottom: **"עדיין אין לך משתמש? הרשם כאן"** (Don't have an account? Register here). This will take you directly to the registration page (`register.html`).
3. Enter your Username, Email, and Password (you can use the 👁️ icon to reveal your password).
4. Click **"הרשם עכשיו ✨"** (Register Now). Your account will be created, and you will be redirected back to log in and access the game lobby (`welcome.html`).
