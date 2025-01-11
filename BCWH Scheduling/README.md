
# 🏥 Pediatrician Scheduling Optimization

This repository contains solutions to optimize shift scheduling for pediatricians at BC Women’s Hospital. The project involves formulating and solving a scheduling problem that satisfies hard constraints while optimizing for soft constraints. The solutions are implemented using **Python** and **Gurobi**.

---

## 📋 Project Overview

### **Objective**
Develop a scheduling solution that:
1. Meets all **hard constraints** related to coverage and availability.
2. Optimally satisfies **soft constraints** to ensure fairness and efficiency.

---

## 🔍 Problem Details

### **1. Input Data**
- **Hard Constraints**:
  - Every shift must be covered by one pediatrician.
  - Total shifts assigned must meet the required number.
  - No consecutive night or back-to-back shifts.
  - Respect individual shift-off requests and weekend limits.

- **Soft Constraints**:
  - Minimize consecutive weekend shifts.
  - Limit the total number of night shifts.
  - Ensure equity between day and night shifts.

### **2. Optimization Problem**
- **Formulation**:
  - The problem is formulated algebraically to balance hard and soft constraints.
  - The objective function minimizes penalties for violating soft constraints.

### **3. Images for Clarity**
- **Images**:
  - Diagrams and constraints included in the project are saved in the **`Images/`** folder for better resolution and reference.
  - These images supplement visual representations in the notebook.

---

## 📂 Repository Contents

| File Name                         | Description                                                  |
|-----------------------------------|--------------------------------------------------------------|
| **`Final_Code_BCWH.ipynb`**       | Jupyter Notebook with the Python implementation and results. |
| **`BCWH_Calculations.xlsx`**      | Input data containing shift requirements and pediatrician availability. |
| **`Project_Info_BCWH.docx`**      | Detailed project description and problem statement.          |
| **`Images/`**                     | Folder containing high-resolution images referenced in the notebook. |

---

## 🎯 Results Summary

### **Base Scenario**:
- Developed a feasible schedule meeting all constraints.
- Summary of shift assignments and penalties minimized.

### **Infeasible Scenario**:
- Modified availability to simulate infeasibility.
- Recommendations:
  1. Adjust shift requirements or pediatrician availability.
  2. Relax specific constraints (e.g., night shift limits).
  3. Increase the number of available pediatricians.

---
