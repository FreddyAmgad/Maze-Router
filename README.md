# 🚀 Maze Router Project - Optimized IC Routing

## 👥 Team Members
- 👨‍💻 Andrew Ishak  
- 👨‍💻 Freddy Amgad  
- 👨‍💻 Kirolous Fouty  
- 👨‍💻 Michael Reda  

---

## 🔍 Overview
The **Maze Router** is a high-performance, grid-based routing tool built for optimizing Integrated Circuit (IC) layouts. It efficiently finds paths across two metal layers—M0 and M1—while minimizing bends and vias to ensure compact and effective routing.

---

## 🔥 Key Features
- ✔ **Multi-Layer Routing** – Supports M0 (horizontal preferred) & M1 (vertical preferred) layers  
- ✔ **BFS-Based Pathfinding** – Implements Breadth-First Search with a penalty-based system for optimized pathfinding  
- ✔ **Obstacle Handling** – Avoids blocked grid cells for realistic IC layout simulation  
- ✔ **Multi-Pin Net Support** – Capable of routing complex nets with multiple pins  
- ✔ **Visualization** – Provides clear 2D plots showing routed paths and obstacles  

---

## 🎯 Challenges Overcome
- ⚡ **Balancing Complexity & Efficiency** – Achieved efficient routing over multiple layers without compromising speed  
- ⚡ **Penalty System** – Developed a cost-aware system that balances shortest paths with minimization of bends and vias  
- ⚡ **Visual Clarity** – Designed an intuitive visualization interface suitable for dense layouts  

---

### ⚙️ Core Components
#### MazeRouter Class
- Grid initialization & obstacle placement  
- Penalty-aware BFS routing  
- Multi-net & multi-pin optimization  

#### Routing Algorithm
- **Layer-Aware BFS:** Prioritizes horizontal routing on M0 and vertical routing on M1  
- **Bend & Via Penalties:** Increases path cost for direction changes and layer switches  

#### Visualization Engine
- Color-coded paths for M0 and M1  
- Clear marking of obstacles and routes  

---

## ⚡ Quick Start

### 📋 Prerequisites
- Python 3.8 or higher  
- Install dependencies:
```bash
pip install matplotlib numpy
