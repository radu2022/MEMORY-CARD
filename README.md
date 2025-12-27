# 🎮 Memory Match Mania

A professional, high-performance **Memory Card Game** built with **React** and **Vite**. This project features a custom-built game logic engine designed for smooth state management and an interactive user experience.

---

## 📸 Screenshots

### Initial State

The game begins with all cards faced down, awaiting the first move.

<img src="./Memorycardgame1.png" alt="Initial Game State" width="300" height="450" item="center"/>

### Game Completion

A dynamic "Congratulations" board appears once all matches are found, displaying your total moves and final score.

<img src="./Memorycardgame2.png" alt="Initial Game State" width="300" height="450" justify="center"/>

---

## ✨ Features

* **Custom React Hook:** Specialized `useGameLogic` hook manages card shuffling, flip states, and match detection.
* **Lazy State Initialization:** Optimized for performance by initializing state within `useState` to prevent unnecessary re-renders on mount.
* **Responsive Design:** A sleek, dark-themed UI that scales beautifully across different screen sizes.
* **Interactive Animations:** Smooth card-flip transitions using 3D CSS transforms (`perspective` and `rotateY`).
* **Match Logic:** Intelligent "locking" mechanism to prevent multiple clicks during the card evaluation window.

---

## 🚀 Tech Stack

* **Frontend:** React 18+
* **Build Tool:** Vite
* **Styling:** CSS3 (Flexbox/Grid & 3D Transforms)
* **Linting:** ESLint (React Hooks rules)

---

## 🛠️ Installation & Setup

1. **Clone the repository:**

   ```bash
function test() {
  console.log("This code will have a copy button to the right of it");
}

   git clone https://github.com/radu2022/MEMORY-CARD.git
```
2. **Navigate to the project directory:**

    ```bash
    cd memory-card-game

3. **Install dependencies:**

    ```bash
    npm install

4. **Start the development server:**

    ```bash
    npm run dev

---

## 🧠 Core Logic

The game utilizes a centralized state machine within a custom hook. It handles:

1. **Lazy Initialization:** The deck is shuffled and prepared once during the initial render using a functional initializer in useState.

2. **Turn Management:** Tracks two cards per turn and determines if they match based on unique ID and value.

3. **Visual Synchronization:** Updates the UI immediately when a card is clicked, while using setTimeout for "flip-back" actions to allow the user to memorize positions.

---

## 📄 License

This project is open-source and available under the MIT License.
