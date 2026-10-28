# Tic-Tac-Toe
<div align="center">

# ⭕ Tic Tac Toe ❌

A clean, responsive two-player Tic Tac Toe game built with **HTML, CSS and vanilla JavaScript**.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

[🎮 Live Demo](https://tic-tac-toe-game-sneha.netlify.app)· [🐛 Report Bug](https://github.com/sneha-goyal7/Tic-Tac-Toe/issues) · [✨ Request Feature](https://github.com/sneha-goyal7/Tic-Tac-Toe/issues)

</div>

---

## 📖 About The Project

Tic Tac Toe is a classic two-player game played on a 3×3 grid. Players take turns placing **O** and **X**, and the first to line up three of their marks in a row, column or diagonal wins. If all 9 boxes are filled with no winner, the game ends in a **draw**.

This project was built to practise **DOM manipulation, event handling and game logic** in vanilla JavaScript.

---

## ✨ Features

- 🎯 Two-player gameplay (**O** and **X** alternate turns)
- 🏆 Automatic winner detection using all 8 winning patterns
- 🤝 Draw detection when the board is full
- 🔁 **Reset Game** button to restart anytime
- 🆕 **New Game** button after a game ends
- 🚫 Boxes get disabled after the game is over (and after being clicked)
- 💬 Winner / draw message display
- 🎨 Clean, simple and responsive UI

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **HTML5**  | Structure of the game board |
| **CSS3**   | Styling and layout |
| **JavaScript (ES6)** | Game logic, DOM manipulation, event handling |

---

## 📂 Project Structure

```
Tic-Tac-Toe/
│── index.html     # Game layout
│── style.css      # Styling
│── script.js      # Game logic
│── README.md      # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
Sirf ek modern web browser (Chrome, Edge, Firefox, etc.). Koi installation ki zarurat nahi.

### Installation & Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/sneha-goyal7/Tic-Tac-Toe.git
   ```
2. **Go to the project folder**
   ```bash
   cd Tic-Tac-Toe
   ```
3. **Open the game**
   - Double-click `index.html`, **or**
   - Use the **Live Server** extension in VS Code (`Right click → Open with Live Server`)

---

## 🎮 How To Play

1. Game **O** se start hota hai.
2. Players baari-baari se kisi empty box par click karte hain.
3. Jo player pehle **3 marks ek line** (row, column ya diagonal) mein laga le, wo jeet jaata hai.
4. Agar sab 9 boxes bhar jaayein aur koi nahi jeeta, to game **Draw** hota hai.
5. **Reset Game** se board clear karo, ya **New Game** se naya round shuru karo.

### 🏁 Winning Patterns

```
Rows:       [0,1,2]  [3,4,5]  [6,7,8]
Columns:    [0,3,6]  [1,4,7]  [2,5,8]
Diagonals:  [0,4,8]  [2,4,6]
```

---

## 🧠 How It Works (Logic)

- Board ke 9 boxes ko `querySelectorAll(".box")` se select kiya gaya hai.
- `turnO` boolean variable track karta hai ki abhi kiski baari hai.
- `count` variable total moves count karta hai taaki **draw** detect ho sake (9 moves = draw).
- `winPatterns` array mein saari 8 winning combinations stored hain, jinhe har move ke baad check kiya jaata hai.
- Game khatam hone par saare boxes disable ho jaate hain aur result message dikhta hai.

---

## 🔮 Future Improvements

- [ ] 🤖 Play vs Computer (AI mode)
- [ ] 📊 Score tracking for both players
- [ ] ✏️ Custom player names
- [ ] 🌗 Dark / Light theme toggle
- [ ] 🔊 Sound effects and animations
- [ ] 🟩 Highlight the winning line

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👩‍💻 Author

**Sneha Goyal**
Final-year B.Tech CSE student | MERN Stack & Gen AI enthusiast

- GitHub: [@sneha-goyal7](https://github.com/sneha-goyal7)
- Email: snehagoyal4295@gmail.com

---

<div align="center">

⭐ **Agar project pasand aaya to repo ko star zaroor karein!** ⭐

</div>
