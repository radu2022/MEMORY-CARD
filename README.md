# 🎮 Memory Match Mania

A professional, high-performance **Memory Card Game** built with **React** and **Vite**. This project features a custom-built game logic engine designed for smooth state management and an interactive user experience.

![Game Demo](./demo.gif) <!-- You can add a demo gif here -->

## 📸 Screenshots

### Game Interface
![Game Interface](./Memorycardgame1.png)

### Game Completion
![Game Completion](./Memorycardgame2.png)

## ✨ Features

* **Custom React Hook:** Specialized `useGameLogic` hook manages card shuffling, flip states, and match detection
* **Lazy State Initialization:** Optimized for performance by initializing state within `useState` to prevent unnecessary re-renders on mount
* **Responsive Design:** A sleek, dark-themed UI that scales beautifully across different screen sizes
* **Interactive Animations:** Smooth card-flip transitions using 3D CSS transforms (`perspective` and `rotateY`)
* **Match Logic:** Intelligent "locking" mechanism to prevent multiple clicks during the card evaluation window
* **Score Tracking:** Real-time tracking of moves and matches
* **Win Condition:** Dynamic celebration screen upon game completion

## 🚀 Tech Stack

* **Frontend:** React 18+
* **Build Tool:** Vite
* **Styling:** CSS3 (Flexbox/Grid & 3D Transforms)
* **Development:** ESLint (React Hooks rules)
* **Icons:** React Icons library
* **State Management:** React Hooks (useState, useEffect, useRef)

## 📦 Installation

### Prerequisites
Make sure you have Node.js (version 16 or higher) installed on your system.

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/radu2022/MEMORY-CARD.git
   
   