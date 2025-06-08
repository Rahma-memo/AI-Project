# AI Project : Robot Navigation using Search Algorithms and Q-Learning

This project explores multiple search and reinforcement learning algorithms applied to a **Robot Navigation Problem** in a grid-based environment. Implemented in Python using a Jupyter Notebook, the project visualizes and compares the performance of various strategies for navigating from a start point to a goal.

## 📁 Contents

- `AI_project_2.ipynb` - Main notebook with implementations and visualizations.
- `README.md` - Project overview (this file).
- `images/` (optional) - Folder to store output visualizations if you export them.

## 🚀 Algorithms Implemented

### 🔍 Uninformed Search
- **Breadth-First Search (BFS)**
- **Depth-First Search (DFS)**
- **Iterative Deepening Search (IDS)**
- **Uniform Cost Search (UCS)**

### 🧠 Informed Search
- **A\* Search**
- **Hill Climbing**
- **Simulated Annealing**

### 🤖 Reinforcement Learning
- **Q-Learning**

## 📊 Features

- Step-by-step robot path visualization for each algorithm.
- Performance metrics comparison (e.g., path length, execution time, memory usage).
- Configurable grid maps, obstacles, start/goal positions.
- Q-Learning agent trained with tunable parameters (alpha, gamma, epsilon).

## 📦 Requirements

Make sure you have Python 3.7+ and the following packages installed:

```bash
pip install matplotlib numpy tqdm
