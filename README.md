# Basic Principles Artificial Intelligence
**Addis Ababa University** **College of Natural and Computational Sciences** **Master of Artificial Intelligence (MSc)**

---

## 👤 Student Information
* **Name:** Mikiyas Mesfin
* **ID Number:** 7944/18
* **Program:** MSc in Artificial Intelligence (Extension)
* **Submitted to:** Dr. Natnael Argaw

---

## 📖 Project Overview
This repository contains a comprehensive set of assignments covering state-space search, adversarial search, and robotics simulation. The project uses the "Traveling Ethiopia" problem as a central theme to demonstrate various Artificial Intelligence strategies.

---

## 📂 Project Tasks & Descriptions

### 1. Uninformed Search Strategies (BFS & DFS)
* **File:** `Task1_1_and_1_2_uninformed.ipynb`
* **Description:** Implementation of Breadth-First Search (BFS) and Depth-First Search (DFS). These algorithms explore the Ethiopian city graph without additional information about the goal's location, ensuring a path is found through brute-force exploration.

### 2. Uniform Cost Search (UCS)
* **File:** `Task_2_1_and_2_2_UCS.ipynb`
* **Description:** Implementation of Uniform Cost Search to find the path with the lowest cumulative travel distance. It uses a priority queue to always expand the node with the lowest path cost $g(n)$.

### 3. Informed Search (A* Algorithm)
* **File:** `Task__3_astar.ipynb`
* **Description:** A more efficient search strategy that uses heuristics (straight-line distances) to guide the agent. It calculates $f(n) = g(n) + h(n)$ to find the optimal path to cities like Moyale with fewer steps than uninformed searches.

### 4. Adversarial Search (MiniMax)
* **File:** `Task_4_minimax.ipynb`
* **Description:** Application of the MiniMax algorithm to a "Coffee Quality" decision tree. This simulates a strategic game where an agent tries to maximize coffee quality while an adversary (or environmental constraint) attempts to minimize it.

### 5. Robotics Simulation (Gazebo & ROS 2)
* **File:** `Task_5_Designing_a_Gazebo_Robot_for_Ethiopia.ipynb`
* **Description:** * **Robot Design:** A three-wheeled robot featuring a differential drive system and a caster wheel.
    * **Sensors:** Integration of a Proximity sensor (LiDAR), Gyroscope (IMU), and RGB Camera.
    * **Environment:** A custom `.world` file representing Ethiopian states in a Cartesian coordinate system.
    * **Integration:** A ROS 2 based Python class that uses BFS to navigate the robot between states in the Gazebo physics engine.

---

## 🛠️ Requirements & Installation

To run these notebooks, you will need:
* Python 3.10+
* ROS 2 Humble (for Task 5)
* Gazebo (for Task 5)

### Clone the Repository
```bash
git clone [https://github.com/Mikiyass/Traveling-Ethiopia-Search-Problem.git](https://github.com/Mikiyass/Traveling-Ethiopia-Search-Problem.git)
