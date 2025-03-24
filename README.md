# 🚇 Driverless Metro Simulation (Route Optimization)
*A project by [Kübra Temel](https://github.com/kubtem)*

## 📌 About the Project
This project simulates an **autonomous metro system** and optimizes routes using **graph-based algorithms**. It provides two main functionalities:  
- **Finding the Least Transfer Route** using **Breadth-First Search (BFS)**  
- **Finding the Fastest Route** using **A* (A-Star) Algorithm**  

This simulation helps visualize how metro networks can be optimized for efficiency, reducing **transfer times** and **overall travel duration**.  

## 🛠️ Technologies Used  
- **Python** 🐍  
- **Jupyter Notebook** 📓  
- **Graph Algorithms** (BFS & A*)  

## 📂 Project Structure
KubraTemel_MetroSimulation/  
│── KubraTemel_MetroSimulation.ipynb   # Jupyter Notebook with code & explanations  
│── README.md                          # Project documentation  

## 🚀 How to Run the Simulation  
1. **Clone the repository:**  
```
git clone https://github.com/kubtem/KubraTemel_MetroSimulation.git
cd KubraTemel_MetroSimulation
```

2.	Open Jupyter Notebook:
```
jupyter notebook KubraTemel_MetroSimulation.ipynb
```

3.	Run all cells to execute the simulation and test different metro routes!
Algorithms Used

## BFS for Least Transfer Route

• Uses queue-based traversal to explore paths level by level.
• Prioritizes paths with the fewest line transfers rather than the shortest distance.

## A* Algorithm for Fastest Route

• Uses priority queues to find the most time-efficient route.
• Heuristic-based approach for faster pathfinding.


### Example Metro Network

Stations and connections modeled in the project:
```
   (A) --5min-- (B) --7min-- (C) --3min-- (D)
    |                                     |
   10min                                 4min
    |                                     |
   (E) ----------------------------------  
```

#### Example test case:

```
route = metro.find_least_transfer_route("A", "D")
print("Least transfer route from A to D:", route)
```

### 📬 Contact

💡 Created by Kübra Temel
📧 Email: kubra.temel@outlook.it
🔗 GitHub: github.com/kubtem

#### This project is open-source and contributions are welcome! 🚀
