{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "6ec96c8b-f19a-4599-8394-895b5af7d34a",
   "metadata": {},
   "source": [
    "# 🚇 Driverless Metro Simulation (Route Optimization)\n",
    "*A project by [Kübra Temel](https://github.com/kubtem)*"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "99e6b047-b75c-4f26-b97e-f082a859056e",
   "metadata": {},
   "source": [
    "## 📌 About the Project  \n",
    "This project simulates an **autonomous metro system** and optimizes routes using **graph-based algorithms**. It provides two main functionalities:  \n",
    "- **Finding the Least Transfer Route** using **Breadth-First Search (BFS)**  \n",
    "- **Finding the Fastest Route** using **A* (A-Star) Algorithm**  \n",
    "\n",
    "This simulation helps visualize how metro networks can be optimized for efficiency, reducing **transfer times** and **overall travel duration**.  "
   ]
  },
  {
   "cell_type": "markdown",
   "id": "bff725e4-9a5e-478d-9638-58f4ff06e1d5",
   "metadata": {
    "jp-MarkdownHeadingCollapsed": true
   },
   "source": [
    "## 🛠️ Technologies Used  \n",
    "- **Python** 🐍  \n",
    "- **Jupyter Notebook** 📓  \n",
    "- **Graph Algorithms** (BFS & A*)  "
   ]
  },
  {
   "cell_type": "markdown",
   "id": "1dca2943-f1ae-41c5-9d73-8bc183542b2d",
   "metadata": {},
   "source": [
    "## 📂 Project Structure"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "458166a1-6648-413f-946a-819c8e7aa0ac",
   "metadata": {},
   "source": [
    "KubraTemel_MetroSimulation/\n",
    "│── KubraTemel_MetroSimulation.ipynb   # Jupyter Notebook with code & explanations  \n",
    "│── README.md                          # Project documentation  "
   ]
  },
  {
   "cell_type": "markdown",
   "id": "da235b34-04f0-4c32-8d12-8ad8a9e72ac0",
   "metadata": {},
   "source": [
    "## 🚀 How to Run the Simulation  \n",
    "1. **Clone the repository:**  \n",
    "```bash\n",
    "git clone https://github.com/kubtem/KubraTemel_MetroSimulation.git\n",
    "cd KubraTemel_MetroSimulation"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "8489a9d9-94f9-4d35-be5a-62be5fbabb93",
   "metadata": {},
   "source": [
    "2. Open Jupyter Notebook:"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "da780874-001a-496a-8341-b9d0bef0121a",
   "metadata": {},
   "source": [
    "```bash\n",
    "jupyter notebook KubraTemel_MetroSimulation.ipynb"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "dafae247-7077-40d1-bca1-d0881cde7fbd",
   "metadata": {},
   "source": [
    "3. Run all cells to execute the simulation and test different metro routes!"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "c66ca78f-8074-4c66-ba2f-9765d0738455",
   "metadata": {},
   "source": [
    "### Algorithms Used\n",
    "\n",
    "#### BFS for Least Transfer Route\n",
    "\t•\tUses queue-based traversal to explore paths level by level.\n",
    "\t•\tPrioritizes paths with the fewest line transfers rather than the shortest distance.\n",
    "\n",
    "####  A* Algorithm for Fastest Route\n",
    "\t•\tUses priority queues to find the most time-efficient route.\n",
    "\t•\tHeuristic-based approach for faster pathfinding.\n",
    "\n",
    "#### Example Metro Network\n",
    "\n",
    "Stations and connections modeled in the project:"
   ]
  },
  {
   "cell_type": "raw",
   "id": "7d09a843-8b0d-495b-8e4c-5bf6254db9aa",
   "metadata": {},
   "source": [
    "   (A) --5min-- (B) --7min-- (C) --3min-- (D)\n",
    "    |                                     |\n",
    "   10min                                 4min\n",
    "    |                                     |\n",
    "   (E) ----------------------------------  "
   ]
  },
  {
   "cell_type": "markdown",
   "id": "6fa7bf91-6af6-414e-9dfd-35d9bc21be5e",
   "metadata": {},
   "source": [
    "Example test case:"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "99e69169-f26a-4352-b036-09e94d4f131b",
   "metadata": {},
   "source": [
    "```bash\n",
    "route = metro.find_least_transfer_route(\"A\", \"D\")\n",
    "print(\"Least transfer route from A to D:\", route)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "0ba77984-c434-4c39-b345-7048547c91aa",
   "metadata": {},
   "source": [
    "## 📬 Contact\n",
    "\n",
    "💡 Created by Kübra Temel\n",
    "📧 Email: kubra.temel@outlook.it\n",
    "🔗 GitHub: github.com/kubtem"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "db50b410-94fa-4474-9c45-361c5a8bb264",
   "metadata": {},
   "source": [
    "This project is open-source and contributions are welcome! 🚀 "
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.11.7"
  },
  "widgets": {
   "application/vnd.jupyter.widget-state+json": {
    "state": {},
    "version_major": 2,
    "version_minor": 0
   }
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
