# Shortest Path Optimization

This project addresses two optimization problems, focusing on transportation and shortest path calculations. Using **Python** and **Gurobi**, the project develops solutions to minimize costs and travel times in logistical and traffic scenarios.

---

## **Project Summary**
### **1. Loggy Lumber Optimization**
#### **Objective**
Minimize the annual cost of transporting lumber from source locations to market locations using trucks and trains.

#### **Problem Summary**
- **Data**: The dataset includes:
  - 15 source locations for lumber.
  - 10 market locations with annual demands.
  - Transportation costs for trucks and trains.
  - Supply and train capacity constraints.
- **Goals**:
  - Optimize transportation mode (truck or train) and quantities to minimize costs.
  - Identify which train routes should be prioritized for negotiations to expand capacity.

#### **Approach**
- Formulated as a cost-minimization problem.
- Solved using Python and Gurobi to find:
  - Optimal transportation routes.
  - Associated costs and decisions for each mode.
  - Analysis of potential train route improvements.

---

### **2. Shortest Path Optimization**
#### **Objective**
Determine the shortest travel time routes from the home intersection (`H`) to each of the intersections (`A`, `B`, `C`, `D`).

#### **Problem Summary**
- **Scenario**:
  - Map data includes 1 km segments with traffic conditions represented by colors:
    - **Green**: 40 km/hr
    - **Orange**: 25 km/hr
    - **Red**: 10 km/hr
  - Bi-directional travel is allowed, and traffic conditions are symmetric.
- **Goal**:
  - Minimize travel time and identify the optimal route from `H` to each destination.

#### **Approach**
- Formulated as a shortest-path problem in a graph structure.
- Solved using Python and Gurobi, incorporating time as the optimization metric.
- Results include:
  - Minimum time required for each route.
  - Detailed path for each destination.

---

## **Contents**
- **`Final_Code_Shortest_Path.ipynb`**: Jupyter Notebook with Python code and optimization solutions.
- **`Data_Shortest_Path.xlsx`**: Data file containing map and transportation costs.
- **`Project_Info_Shortest_Path.docx`**: Detailed problem statements and background.

---

## **Results**
- **Loggy Lumber Optimization**:
  - Annual cost of meeting lumber demand.
  - Recommendations for prioritizing train route negotiations.
- **Shortest Path Optimization**:
  - Travel times and routes from `H` to `A`, `B`, `C`, and `D`.
  - Traffic impact analysis on travel efficiency.

---

## **How to Run**
1. Install the required dependencies:
   ```bash
   pip install gurobipy pandas numpy matplotlib

