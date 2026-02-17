# 🚀 ALPHA – Your Intelligent Virtual Companion

ALPHA is a full-stack web-based voice assistant that allows users to interact with a computer using natural voice commands. The system listens to the user, understands the intent, responds intelligently using AI, and performs real-time browser actions like searching Google, opening YouTube, and providing information such as weather updates.

It works similar to **Google Assistant / Siri**, but completely built using web technologies.

---

## 🌟 Features

### 🔐 Authentication

* Secure user registration & login (JWT)
* Password hashing
* Protected API routes
* User-specific assistant profile

### 🎙 Voice Interaction

* Wake word activation — “Alpha”
* Speech-to-Text command recognition
* Text-to-Speech response
* Continuous listening animation

### 🤖 AI Intelligence

* Answers general knowledge questions
* Explains programming concepts
* Conversational responses
* Context-aware replies

### 🌐 Smart Browser Automation

* Opens YouTube and searches videos
* Redirects to Google search results
* Provides real-time weather information

### 🎨 Personalization

* Choose assistant avatar
* Set custom assistant name
* Persistent assistant identity

---

## 🖼 Application Screenshots

## 📝 Authentication & Setup

### Signup
![signup](https://github.com/drsudeep/ALPHA-Voice-Based-Virtual-Assistant/blob/main/Signup%20Page%20Alpha.png?raw=true)

### Login
![Login](https://github.com/drsudeep/ALPHA-Voice-Based-Virtual-Assistant/blob/main/Login%20Page%20Alpha.png?raw=true)

### Choose Assistant Avatar
![Avatar Selection](https://github.com/drsudeep/ALPHA-Voice-Based-Virtual-Assistant/blob/main/Choose%20Assistant%20Avatar.png?raw=true)

### Name Your Assistant
![Assistant Name](https://github.com/drsudeep/ALPHA-Voice-Based-Virtual-Assistant/blob/main/Name%20Your%20Assistan.png?raw=true)


### 🧠 Answering Questions
 
![ask](https://github.com/drsudeep/ALPHA-Voice-Based-Virtual-Assistant/blob/main/Asking%20queries.png?raw=true) User asking question)
![ans](https://github.com/drsudeep/ALPHA-Voice-Based-Virtual-Assistant/blob/main/Ans%20for%20query.png?raw=true) (Assistant giving answer)

### ▶ Opening YouTube

![yt](https://github.com/drsudeep/ALPHA-Voice-Based-Virtual-Assistant/blob/main/Voice%20command%201.png?raw=true) (Voice command)
![res](https://github.com/drsudeep/ALPHA-Voice-Based-Virtual-Assistant/blob/main/YouTube%20opened%20with%20results.png?raw=true) (YouTube opened with results)

### 🌍 Redirecting to Google

![v2](https://github.com/drsudeep/ALPHA-Voice-Based-Virtual-Assistant/blob/main/Voice%20command%202.png?raw=true)### Voice command
![res2](https://github.com/drsudeep/ALPHA-Voice-Based-Virtual-Assistant/blob/main/Google%20search%20page.png?raw=true)![Uploading image.png…](Google search page)

### 🌦 Weather Updates

![v3](https://github.com/drsudeep/ALPHA-Voice-Based-Virtual-Assistant/blob/main/Voice%20command%203.png?raw=true) ### Voice command
![res3](https://github.com/drsudeep/ALPHA-Voice-Based-Virtual-Assistant/blob/main/Weather%20result%20displayed.png?raw=true) ### Weather result displayed

---

## 🛠 Tech Stack

### Frontend

* React JS (Vite)
* Tailwind CSS
* Web Speech API (Speech Recognition & Speech Synthesis)
* Context API
* Axios

### Backend

* Node.js
* Express.js
* MongoDB
* JWT Authentication
* Multer (file handling)
* Cloudinary (image storage)

### AI Integration

* Gemini API – Natural language response generation

---

## 📂 Project Structure

```
ALPHA/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│
├── backend/
│   ├── config/
│   │   ├── cloudinary.js
│   │   ├── db.js
│   │   └── token.js
│   │
│   ├── controllers/
│   │   ├── auth.controllers.js
│   │   └── user.controllers.js
│   │
│   ├── middlewares/
│   │   ├── isAuth.js
│   │   └── multer.js
│   │
│   ├── models/
│   │   └── user.model.js
│   │
│   ├── routes/
│   │   └── user.routes.js
│   │
│   ├── gemini.js
│   ├── index.js
│   └── .env
│
└── README.md
```

---

## ⚙ Installation

### Backend

```bash
cd backend
npm install
npm run dev
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 📌 How It Works

1. User registers and logs in
2. Chooses assistant avatar and name
3. Activates assistant using voice
4. Speech converted to text
5. Command sent to backend
6. AI processes the intent
7. Assistant responds using voice
8. Performs actions (Google / YouTube / Weather / Answer)

---

## 🎯 Future Enhancements

* Mobile application
* Offline voice recognition
* Smart home control
* Multi-language support
* Chat history memory
* Reminder & alarm scheduling

---

## 📖 About

ALPHA demonstrates real-time Human Computer Interaction using voice recognition, AI reasoning, and browser automation. It showcases how modern AI assistants can be implemented entirely using web technologies.

---

## 💻 Languages Used

* JavaScript – Frontend & Backend
* HTML/CSS – UI
* MongoDB – Database

---

⭐ If you like this project, give it a star!
