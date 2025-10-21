
# tic-tac-toe-react
A game made in react js
Tic-Tac-Toe React Game

A simple, interactive Tic-Tac-Toe game built with **React** ⚛️ — designed to practice React fundamentals such as state management, props, event handling, and component communication.

---

## 🚀 Features

- 🎮 Playable Tic-Tac-Toe board (X vs O)
- 🔁 Alternating player turns
- 🏆 Winner detection logic
- 🚫 Prevents overwriting filled squares
- 🧱 Clean component structure (Square + Board)
- ⚡ Fast refresh with modern React setup (Vite or CRA)

---

## 🧠 Concepts Covered

- `useState()` hook for managing component state
- **Lifting state up** to share data between components
- **Conditional rendering** for dynamic UI updates
- **Pure functions** for handling game logic (`calculateWinner`)

---

## 🏗️ Project Structure

tic-tac-toe/
├── src/
│ ├── Board.jsx
│ ├── Square.jsx
│ ├── index.js
│ └── App.css
├── package.json
├── README.md
└── ...

yaml
Always show details

Copy code

---


## ⚙️ Setup & Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/tic-tac-toe-react.git
   cd tic-tac-toe-react
Install dependencies

bash
Always show details

Copy code
npm install
Run the development server

bash
Always show details

Copy code
npm run dev
or, if using Create React App:

bash
Always show details

Copy code
npm start
Open your browser and go to:
👉 http://localhost:5173 or http://localhost:3000

🧩 Core Files
File	Description
Square.jsx	Handles individual square rendering and click events
Board.jsx	Manages overall game state, player turns, and winner detection
calculateWinner()	Determines the game winner based on square combinations
App.css	Basic styling for board layout and appearance



🏁 Future Improvements

🔁 Add Restart/Reset button - Checked

🧮 Implement score tracking

🤖 Add AI opponent (single-player mode)

🎨 Improve UI with animations (Framer Motion)

🧑🏽‍💻 Author

Matrix-Node, CS Student
