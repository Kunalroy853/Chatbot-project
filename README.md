# 🤖 Secure Chatbot with OTP Authentication

## 📌 Overview

This project is a secure chatbot application built using Streamlit and Python. It includes user authentication using Time-based One-Time Password (TOTP), adding an extra layer of security.

---

## 🚀 Features

* 🔐 User Registration & Login
* 📱 QR Code for Google Authenticator
* 🔢 OTP-based Authentication (TOTP)
* 💬 Simple Chatbot Interaction
* 🗂️ SQLite Database Integration

---

## 🛠️ Tech Stack

* Python
* Streamlit
* PyOTP
* SQLite
* QR Code

---

## ⚙️ How to Run

1. Install dependencies:

```
pip install -r requirements.txt
```

2. Run the application:

```
streamlit run app.py
```

3. Open in browser:

```
http://localhost:8501
```

---

## 📂 Project Structure

```
chatbot-auth/
│
├── app.py
├── requirements.txt
└── README.md
```

---

## 🎯 How It Works

* User registers and gets a QR code
* QR is scanned in Google Authenticator
* User logs in using username, password, and OTP
* After login, chatbot interface is available

---

## 📚 Learning Outcomes

* Understanding of authentication systems
* Implementation of TOTP security
* Working with Streamlit for web apps
* Basic chatbot development

---

## 🚀 Future Improvements

* Add AI-based chatbot (NLP)
* Improve UI/UX
* Add password hashing
* Deploy online

---

## 👤 Author

Kunal Roy

---

## ⭐ Note

This is a beginner-friendly project demonstrating secure authentication with a chatbot system.
