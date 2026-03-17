# 🗺️ AI Treasure Hunt — BFS, DFS & A*

An interactive maze-based game that visually demonstrates three classic AI pathfinding algorithms: **Breadth-First Search (BFS)**, **Depth-First Search (DFS)**, and **A\* (A-Star)**. Built as a college AI project to show how different algorithms explore a grid to find a hidden treasure.

---

## 🎮 Live Demo

👉 [Play it here](https://your-username.github.io/ai-treasure-hunt/ai_treasure_hunt_bfs_dfs_astar.html)

> Replace `your-username` with your actual GitHub username after enabling GitHub Pages.

---

## 📸 Preview

The explorer 🧭 must find the treasure 💰 through a randomly generated maze. Watch each algorithm explore cells in real time, then trace the final path.

---

## 🧠 Algorithms Used

| Algorithm | Strategy | Shortest Path? | Color |
|-----------|----------|---------------|-------|
| **BFS** | Explores level by level using a Queue | ✅ Always | 🔵 Blue |
| **DFS** | Dives deep using a Stack, backtracks | ❌ Not always | 🔴 Red |
| **A\*** | Uses heuristic (Manhattan distance) to guide search | ✅ Always | 🟢 Green |

### How each works:
- **BFS** — Uses a queue (FIFO). Expands all neighbors at the current depth before going deeper. Guarantees the shortest path but visits many cells.
- **DFS** — Uses a stack (LIFO). Follows one path as deep as possible before backtracking. Memory efficient but may find a longer path.
- **A\*** — Uses a priority queue sorted by `f = g + h`, where `g` = cost from start and `h` = Manhattan distance to goal. Smartest and most efficient of the three.

---

## ✨ Features

- 🔽 Dropdown to switch between BFS, DFS, and A* instantly
- ▶️ Animated step-by-step visualization of exploration
- 🎚️ Speed slider to slow down or speed up the animation
- 🖱️ Click cells to draw/erase walls and build custom mazes
- 🧭 Drag the Start and Treasure icons to reposition them
- 📊 Live statistics: cells visited and path length
- 📝 Log panel narrating each algorithm's run
- 🔄 "New Maze" button to generate a fresh random maze

---

## 🚀 How to Run

### Option 1 — Open directly (no setup needed)
Just download `ai_treasure_hunt_bfs_dfs_astar.html` and open it in any modern browser.

### Option 2 — GitHub Pages (live link)
1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Visit `https://your-username.github.io/ai-treasure-hunt/ai_treasure_hunt_bfs_dfs_astar.html`

---

## 📁 Project Structure

```
ai-treasure-hunt/
│
├── ai_treasure_hunt_bfs_dfs_astar.html   # Main game file (single file, fully self-contained)
├── README.md                              # Project documentation
└── .gitignore                             # Git ignore rules
```

---

## 🛠️ Tech Stack

- **HTML5 Canvas** — for drawing the grid and animations
- **Vanilla JavaScript** — all algorithm logic and interactivity
- **CSS3** — styling and layout
- **Google Fonts** — Cinzel & Crimson Text for the treasure-hunt aesthetic

No frameworks. No dependencies. Just open and play.

---

## 📚 Concepts Demonstrated

- Graph traversal (BFS, DFS)
- Heuristic search (A*)
- Queue vs Stack data structures
- Manhattan distance as a heuristic
- Pathfinding via parent pointer backtracking
- Interactive algorithm visualization

---

## 👨‍💻 Team

Made with ❤️ as part of an AI course project.

---

## 📄 License

MIT License — free to use, modify, and share.
