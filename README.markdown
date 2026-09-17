# Javascript Chess Game by Faria Afrin
# ♟️ Neon JavaScript Chess Game

> 🌐 **Live Demo:** [Play the Game Here](https://YOUR_USERNAME.github.io/YOUR_REPOSITORY_NAME/)

A lightweight, interactive, and visually striking Chess game built using pure JavaScript, jQuery, HTML5, and CSS3. The project features eye-catching neon visual effects, dynamic movement hints, and fully functional chess mechanics including standard movement, capturing pieces, and castling.

## ✨ Features

- **Full Chess Logic:** Supports all standard piece movements (Pawns, Rooks, Knights, Bishops, Queens, and Kings).
- **Movement Highlighting:** Valid paths are dynamically lit up in green to guide players during their turn.
- **Turn Management:** Seamless tracking and validation between White and Black player turns.
- **Special Moves:** Functional programming logic implemented for King-side castling.
- **Neon Aesthetic & Animations:** Features interactive, hovering neon text glow effects and CSS shake animations (`CSShake`) when highlighting available moves.
- **Anti-Cheat:** Disabled context menus to keep the focus purely on the gameplay grid.

## 🛠️ Built With

- **HTML5:** For the structured 8 × 8 grid layout.
- **CSS3:** For the custom styling, keyframe animations (`@keyframes`), and custom neon effects.
- **JavaScript (ES6):** For core game state variables, coordinate-based grid systems, and path tracking.
- **jQuery:** For rapid DOM manipulation, event listeners, and seamless class toggles.

## 🚀 Getting Started

### Prerequisites
You only need a modern web browser (like Google Chrome, Mozilla Firefox, or Microsoft Edge) to run this game. No installation or server setups are required!

### Installation & Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
   ```

2. **Navigate into the project directory:**
   ```bash
   cd YOUR_REPOSITORY_NAME
   ```

3. **Launch the game:**
   Simply double-click your primary HTML file (make sure it is named `index.html`) to open and play the game instantly in your browser.

## ⚙️ How to Turn on the Live Link (GitHub Pages)

To make your live link work on GitHub, follow these quick steps:
1. Go to your repository on **GitHub**.
2. Click on the **Settings** tab at the top right.
3. Scroll down the left sidebar and click on **Pages**.
4. Under **Build and deployment**, change the Source branch to **`main`** (or `master`).
5. Click **Save**. Your game will be live online in about 1–2 minutes!

## 🕹️ How to Play

1. The game initializes with a message indicating it is **White's Turn**.
2. **Select a Piece:** Click on any of your own pieces. The grid cells representing valid paths or open capture blocks will start shaking and glow neon green.
3. **Change Selection:** Click on another one of your pieces to quickly switch focus and inspect its legal moves instead.
4. **Move or Capture:** Click on any highlighted green cell to advance your piece or capture an opponent's piece standing on that coordinate.
5. Once a valid action completes, control safely transitions to the next player.

## 📂 File Architecture

- **`index.html`** – Outlines the board canvas wrapper, cell grids, and real-time turn banners.
- **`style.css`** – Houses core page alignments, responsive board parameters, custom `@keyframes`, and target animations.
- **`script.js`** – Coordinates game setup initialization arrays, piece object mapping, strict block boundary filtering rules, and win/turn tracking rules.

## 📄 License

This project is licensed under the MIT License - see the local license files for details. (Includes open-source snippet integrations from `CSShake` by @elrumordelaluz).


