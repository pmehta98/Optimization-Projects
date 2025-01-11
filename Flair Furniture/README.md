# Flair Furniture and Advertising Optimization

This project addresses two separate optimization problems using Python and Gurobi to solve real-world business challenges. Below are the details:

---

## **1. Flair Furniture Optimization with Quantity Discounts**
### **Objective**
Maximize profit while considering quantity discounts on furniture production.

### **Problem Summary**
- **Profit Margins**:
  - Tables: $7 per table for the first 150 tables, then $3 per table beyond 150.
  - Chairs: $5 per chair for the first 300 chairs, then $4 per chair beyond 300.
- The optimization problem determines:
  - The optimal number of tables and chairs to produce.
  - The maximum profit achievable under these conditions.

### **Approach**
- Formulated as a linear programming problem with constraints and piecewise profit margins.
- Solved using Python and Gurobi.
- Comparison with the baseline solution to explain the impact of quantity discounts on profit margins.

---

## **2. Advertising Optimization**
### **Objective**
Minimize the total cost of an advertising campaign while meeting specific business goals.

### **Problem Summary**
- The advertising campaign involves three mediums: **television**, **radio**, and **newspaper**.
- Goals:
  1. Spend no more than $25,000 on advertising.
  2. Reach at least 30,000 new potential customers.
  3. Run at least 10 television ads.
- Penalties:
  - $1 per dollar over the budget.
  - $5 per customer short of 30,000.
  - $100 per TV ad short of 10.

### **Approach**
- Formulated as a goal programming problem.
- Solved using Python and Gurobi.
- The solution includes the optimal number of advertisements for each medium and the resulting cost.

---

## **Contents**
- **`Final_Code_FF.ipynb`**: Jupyter Notebook with the Python implementation and Gurobi solutions for both problems.
- **`Project_Info_FF.docx`**: Detailed problem statements, constraints, and objectives.

---

## **How to Run**
1. Install the required dependencies:
   ```bash
   pip install gurobipy numpy pandas matplotlib

