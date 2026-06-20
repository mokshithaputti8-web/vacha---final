# 🌍 Vacha – Language Learning Flashcard App

A beautiful spaced-repetition flashcard app for German, Japanese and Korean.

---

## 🚀 How to Run (Terminal / Node.js)

### Step 1 — Install Node.js
Download from https://nodejs.org  (choose the LTS version)
After installing, restart your computer.

### Step 2 — Open this folder in VS Code
- Open VS Code
- File → Open Folder → select the `vacha-language-learning` folder

### Step 3 — Open the Terminal in VS Code
Press: Ctrl + ` (backtick key, top-left of keyboard)

### Step 4 — Install dependencies
Type this and press Enter:
```
npm install
```
Wait about 1–2 minutes. You'll see many packages installing.

### Step 5 — Start the app
```
npm start
```
Your browser opens automatically at http://localhost:3000 🎉

---

## 📁 Project Structure

```
vacha-language-learning/
├── public/
│   └── index.html              ← HTML entry point
├── src/
│   ├── index.js                ← React entry point
│   ├── index.css               ← Global styles (Deep Blue + Gold theme)
│   ├── App.jsx                 ← Root app with Router + state
│   ├── data/
│   │   └── flashcards.js       ← All 30 cards (German, Japanese, Korean)
│   ├── hooks/
│   │   └── useProgress.js      ← SRS progress tracking hook
│   ├── components/
│   │   ├── Navbar.jsx          ← Sticky navigation bar
│   │   ├── Footer.jsx          ← Footer with links
│   │   ├── Flashcard.jsx       ← 3D flip card + SRS rating buttons
│   │   ├── QuizArena.jsx       ← MCQ quiz with 15s countdown timer
│   │   ├── ProgressChart.jsx   ← Accuracy + completion bars per language
│   │   ├── DeckManager.jsx     ← Browse, add and delete flashcards
│   │   └── Notification.jsx    ← Toast notification system
│   └── pages/
│       ├── Home.jsx            ← Landing page with hero + features
│       ├── Dashboard.jsx       ← Stats + progress charts
│       ├── LanguagePage.jsx    ← Shared page for all 3 languages
│       └── About.jsx           ← About + tech stack
└── package.json
```

---

## ✨ Features

| Feature | Description |
|---|---|
| 🧠 Spaced Repetition | Rate cards Again / Hard / Good / Easy — SRS algorithm |
| 🎯 Quiz Arena | 8 MCQ questions per session with 15s timer |
| 🔊 Audio Pronunciation | Web Speech API native-style pronunciation |
| 📈 Progress Tracking | Accuracy bars, streaks, dot-history per language |
| 🗂️ Deck Manager | Add custom cards, filter by tag, delete cards |
| 🔔 Notifications | Toast alerts after every interaction |
| 🌍 3 Languages | German 🇩🇪, Japanese 🇯🇵, Korean 🇰🇷 |

---

## 🎨 Color Theme

| Color | Hex |
|---|---|
| Deep Blue | #0A1F44 |
| Light Blue | #3BAFDA |
| Golden Yellow | #FFD700 |
| White | #FFFFFF |

---

## 🛠️ Tech Stack

- React 18
- React Router 6
- Custom CSS (no Tailwind/Bootstrap needed)
- Web Speech API
- Create React App

---

Built with ❤️ for Problem 142 – Language Learning Flashcard App (Advanced Level)
