# 🌯 Burrito Optimization Game

This repository contains solutions and analyses for the **Burrito Optimization Game**, focusing on predictive and prescriptive analytics to optimize truck placement and demand fulfillment. Using **Python** and **Gurobi**, the project solves various optimization problems and explores strategic insights for improving operational decisions.

---

## 📋 Project Overview

### **Objective**
Optimize the placement of burrito trucks and the allocation of demand to maximize profit while analyzing trade-offs and operational constraints.

---

## 🔍 Problem Details

### **1. Predictive Analytics**
- **Goal**: Estimate a function \( f(d) \) to predict the fraction of demand traveling a distance \( d \) for a burrito.
- **Approach**: Fit a predictive model using provided data to determine the relationship between distance and demand.

---

### **2. Optimization Problem**
- **Goal**: Set up and solve an integer programming (IP) model to:
  1. Place trucks at optimal locations.
  2. Allocate demand from buildings to trucks.
  3. Maximize overall profit.

#### **Constraints**:
1. Truck placement limited to specified locations.
2. Unlimited truck capacity in the base model.
3. Demand allocation scales based on distance.

#### **Scenarios**:
- Increased ingredient costs across days.
- Limited truck capacity with and without multiple trucks per location.
- Comparison of solutions under different capacity assumptions.

---

## 📂 Repository Contents

| File Name                             | Description                                                  |
|---------------------------------------|--------------------------------------------------------------|
| **`Final_Code_Burrito_Optimization.ipynb`** | Jupyter Notebook with Python implementation and solutions.   |
| **`Project_Info_Burrito_Optimization.docx`** | Detailed problem statements and background information.      |
| **`round1-day1_problem_data.csv`**    | Cost and revenue parameters for Day 1.                      |
| **`round1-day1_demand_node_data.csv`**| Coordinates and demand of buildings.                        |
| **`round1-day1_truck_node_data.csv`** | Coordinates of truck locations.                             |
| **`round1-day1_demand_truck_data.csv`** | Distances and scaled demand between buildings and trucks.    |

---

## 🎯 Results Summary

### **Predictive Analytics**:
- Developed a distance-based demand prediction function \( f(d) \) using regression techniques.

### **Optimization Models**:
- **Unlimited Capacity**:
  - Optimal truck placements and demand allocations.
  - Total profit and insights into cost-revenue trade-offs.
- **Limited Capacity**:
  - Enhanced model to include truck capacity constraints.
  - Compared results for scenarios with and without multiple trucks per location.
  - Insights into operational decisions and strategic planning.

---
