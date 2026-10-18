# Infinite Us ♾️

A soothing, web-based Canvas animation that dynamically arranges over 400 unique translations and expressions of the word "Love" into a perfect infinity symbol.

Originally conceptualized in Python, this HTML5 port utilizes a custom masking algorithm to pack words tightly into mathematical geometric boundaries with absolutely zero repetitions, finished with a continuous flowing wave animation.

## ✨ Features

* **Zero-Repetition Packing Algorithm:** Dynamically measures and fits over 400 unique strings into a custom shape without ever repeating a single word.
* **Mathematical Masking:** Uses overlapping teardrop functions and Canvas compositing (`destination-out`) to generate a crisp infinity loop (∞) boundary.
* **Flowing Wave Animation:** Once settled, an omni-directional, glowing wave continuously sweeps through the text track, calculating intensity based on absolute angular distance.
* **Pastel Aesthetic:** Features a soothing, MacBook-inspired pastel color palette, perfectly mapped to the coordinate geometry.

## 🛠️ Tech Stack

* **HTML5 Canvas API** for high-performance rendering.
* **Vanilla JavaScript (ES6)** for math, physics, and animation loops.
* **CSS3** for minimal layout styling and glowing drop-shadows.

## 🚀 How to Run

This project is entirely front-end and requires no build steps, dependencies, or local servers.

1. Clone the repository:
```bash
git clone https://github.com/yourusername/infinite-us.git

```


2. Navigate to the project folder.
3. Simply double-click `index.html` (or open it directly in any modern web browser like Chrome, Edge, or Safari).

## 💡 Code Structure Overview

* **`getBestFit()`**: The core logic that searches the shuffled dictionary array to find the perfect word that fits the remaining pixel gap on any given line.
* **`drawTeardrop()`**: Generates the vector shapes used to carve out the negative space for the infinity loop.
* **`draw()`**: The main `requestAnimationFrame` loop that handles the spawning lift-and-drop physics, followed by the continuous glowing wave effect.
