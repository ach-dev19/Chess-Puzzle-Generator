# ChessMD ♟️🩺

> **A healthy mind makes strong moves.**

Kids often get nervous, rush, or give up after a single mistake at chess tournaments. **ChessMD** is an interactive web application designed to train young chess players' tactical moves *and* mental resilience, helping them practice staying calm, focused, and confident under pressure.

---

## 🚀 Live Demo

Experience the app live in your browser:
🎯 **[Launch ChessMD Application](https://ach-dev19.github.io/Chess-Puzzle-Generator)**

---

## ✨ Features

- **FEN-Based Puzzles:** Chess puzzles are dynamically parsed and loaded straight from Forsyth-Edwards Notation (FEN) positions.
- **Mental Check-in:** A reflective mood check-in step before training begins to gauge player mindset.
- **Doctor's Notes:** Real-time feedback and smart nudges that trigger if a player rushes their moves or misses a tactic twice.
- **Check-up Results:** A dual-layered dashboard showing both a traditional **board review** and an insightful **mind review** after every puzzle.
- **Dr. Chess (AI Coach):** An embedded AI mentor that evaluates exactly which puzzle you completed, tracks how it went, and delivers custom encouragement.

---

## 🛠️ How It Works

1. **Data Schema:** Each individual puzzle stores its unique FEN, correct answer matrix, mind-game lesson data, specialized review triggers, and target coach context.
2. **State Tracking:** The application tracks active metrics behind the scenes, including:
   - Total time elapsed per puzzle
   - Incorrect move attempts
   - Hint usage patterns
3. **Evaluation Pipeline:** The app matches player metrics to the appropriate review sequence, compiles the telemetry, and securely feeds the contextual framework to the AI engine.

---

## 💻 Tech Stack

### Frontend & Logic
- **Core Architecture:** HTML5, CSS3, JavaScript (ES6+)
- **Chess Engine Utilities:** `[chess library, if used]` *(e.g., chess.js, chessboard.js)*

### AI Integration
- **Engine Host:** `[AI service used for the coach]` *(e.g., OpenAI API, Google Gemini API)*

---

## 🤖 AI Disclosure

- **Development Assistance:** `[Which AI tools helped and with what.]` *(e.g., ChatGPT helped optimize the FEN parsing logic and style the board layout)*

---

## 💡 Why I Built This

I participate in competitive chess tournaments and coach younger students at my local library's chess club. Time and again, I have witnessed how one minor mistake can cause kids (and even experienced players) to completely lose their confidence and crumble during a game. 

I designed and engineered **ChessMD** to break that cycle—creating a sandbox environment where young players learn to treat mistakes as clinical data points rather than psychological setbacks.

---

## 🔮 What's Next

- [ ] Scale up the database with a larger variety of tactical puzzles
- [ ] Conduct wider testing cohorts with more students at the library chess club
- [ ] Implement analytics dashboards to track and quantify improvements in player confidence over time

---

### ⚠️ Disclaimer
*\*Dr. Chess is an AI educational coach designed to train sports psychology frameworks in chess; it does not provide medical advice or real clinical diagnoses.*
