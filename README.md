# 🎮 Coin Collector Mini-Game

A lightweight, arcade-style 2D mini-game built entirely with HTML5 Canvas and vanilla JavaScript. Avoid the pursuing enemy, navigate the map, and collect all the gold coins to win!

---

## 🚀 Live Demo

You can play the game instantly by opening the `index.html` file in any modern web browser.

---

## 🕹️ How to Play

### Objective
Collect all **3 gold coins** scattered across the map while avoiding the **red enemy** that relentlessly chases you.

### Controls
Use your keyboard's **Arrow Keys** to move the player around the canvas:
* `▲ Arrow Up` - Move Up
* `▼ Arrow Down` - Move Down
* `◀ Arrow Left` - Move Left
* `▶ Arrow Right` - Move Right

### Game Rules
* **🔵 Blue Square:** You (The Player).
* **🟡 Gold Squares:** Coins to collect.
* **🔴 Red Square:** The Enemy (Chases you down using simple vector tracking).
* **💀 Game Over:** Triggered if the enemy collides with you.
* **🎉 Victory:** Triggered the moment you collect all coins.

---

## 🛠️ Features & Technical Details

* **No Dependencies:** Built with pure vanilla JavaScript, HTML5, and CSS3.
* **Real-time Mechanics:** Features a continuous game loop managed by `requestAnimationFrame` for buttery-smooth rendering.
* **Collision Detection:** Implements efficient Axis-Aligned Bounding Box (AABB) algorithms to calculate player, coin, and enemy overlapping.
* **AI Pathfinding:** The enemy utilizes simple normalized vector mechanics to dynamically calculate distance and steer directly toward the player's current $x, y$ coordinates.

---

## 📂 Installation & Setup

No installation or server setup is required. 

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git](https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git)