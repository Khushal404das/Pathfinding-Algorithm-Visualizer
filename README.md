#  Pathfinding Algorithm Visualizer  
**By:** Khushal Das (22P9341)  

An **interactive educational tool** for visualizing and comparing fundamental graph traversal and shortest-path algorithms including **BFS**, **Dijkstra’s**, **Bellman-Ford**, and **Floyd-Warshall**.  
This desktop application aims to make algorithmic learning **intuitive**, **interactive**, and **visual** for students, educators, and developers.

---

##  Executive Summary
The **Interactive Pathfinding Algorithm Visualizer** is designed to help users understand how popular pathfinding algorithms operate internally.  
It provides **real-time visualization**, **step-by-step execution**, and **performance comparison** between algorithms — all within a simple and clean **Tkinter GUI**.

---

##  Project Objectives

### Primary Goals
- **Educational Enhancement:** Make complex algorithmic concepts easy to understand through visualization.  
- **Interactive Learning:** Allow users to manipulate graphs and control execution speed.  
- **Algorithm Comparison:** Compare the efficiency and behavior of multiple algorithms side-by-side.  
- **Real-time Feedback:** Provide visual and textual updates as the algorithm progresses.

### Secondary Goals
- Support multiple graph configurations and edge cases.  
- Display algorithm performance metrics.  
- Allow import/export of graph configurations for classroom or project use.  
- Enable flexible playback controls for self-paced learning.

---

##  Technical Specifications

### Core Technologies
| Component | Technology |
|------------|-------------|
| **Programming Language** | Python 3.x |
| **GUI Framework** | Tkinter |
| **Graph Processing** | NetworkX |
| **Visualization** | Matplotlib (integrated with Tkinter Canvas) |
| **Data Structures** | Custom priority queues, distance matrices, state management |

### System Requirements
- **OS:** Windows / macOS / Linux  
- **Python Version:** 3.7+  
- **RAM:** Minimum 512 MB  
- **Storage:** 50 MB available disk space  
- **Display:** 1024×768 (recommended: 1400×800 or higher)

---

##  Key Features

###  Algorithm Implementations
| Algorithm | Time Complexity | Key Features |
|------------|-----------------|---------------|
| **Breadth-First Search (BFS)** | O(V + E) | Unweighted graphs, queue-based, level-by-level exploration |
| **Dijkstra’s Algorithm** | O((V + E) log V) | Non-negative weights, priority queue, distance relaxation |
| **Bellman-Ford Algorithm** | O(V × E) | Supports negative weights, edge relaxation, convergence detection |
| **Floyd-Warshall Algorithm** | O(V³) | All-pairs shortest paths, dynamic programming approach |

---

##  Interactive Features
- **Graph Editing:** Add or remove nodes and edges dynamically.  
- **Node Selection:** Click-based start/end point selection.  
- **Real-time Modification:** Edit graphs during visualization.  
- **Visual Feedback:** Color-coded states for visited, current, and shortest path nodes.  
- **Step Control:** Manual stepping, play/pause, and adjustable speed.

---

##  Visualization Components
- **Graph Display:** Dynamic rendering using Matplotlib.  
- **Algorithm Tables:** Real-time visualization of data structures (queues, matrices, etc.).  
- **Execution Log:** Step-by-step textual breakdown.  
- **Performance Metrics:** Display of complexity and execution statistics.

---

##  User Interface Design

### Layout
**Left Panel (60%)**
- Graph creation tools  
- Algorithm selection  
- Playback controls  
- Main visualization area  

**Right Panel (40%)**
- Algorithm-specific data tables  
- Execution log  
- Performance metrics display  

### User Experience
- Intuitive controls with labeled buttons  
- Color-coded consistency  
- Responsive layout  
- Error handling and validation  
- Tooltips and algorithm descriptions  

---

##  Educational Value

### Learning Outcomes
Users will:
- Understand the internal working of major pathfinding algorithms  
- Compare algorithmic efficiency and complexity  
- Visualize data structures (queues, matrices, etc.)  
- Learn to choose suitable algorithms for problem contexts  

### Pedagogical Benefits
- Encourages **active learning** through interaction  
- Promotes **visual understanding**  
- Supports **self-paced exploration**  
- Provides **immediate feedback** on actions  

---

##  Implementation Phases

| Phase | Description | Status |
|--------|--------------|--------|
| **Phase 1** | Core development (basic algorithms, visualization, interactivity) | ✅ Completed |
| **Phase 2** | UX improvements, testing, documentation |  In Progress |
| **Phase 3** | Import/export, benchmarking, themes, session saving |  Planned |
| **Phase 4** | Packaging, tutorials, feedback integration |  Planned |

---

##  Technical Architecture

### Core Components
1. **Graph Management System:** Handles graph data using NetworkX.  
2. **Algorithm Engine:** Step-by-step execution using Python generators.  
3. **Visualization Layer:** Matplotlib integrated into Tkinter canvas.  
4. **State Management:** Tracks algorithm progress and UI updates.  
5. **UI Controller:** Manages events and user interactions.

### Data Flow
