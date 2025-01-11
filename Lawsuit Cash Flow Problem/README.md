# Optimization Projects

This repository contains solutions to two optimization problems focusing on real-world applications. The solutions use **Python** and **Gurobi**, a powerful optimization solver. Below are the details of the two projects included in this repository:

---

## **1. Lawsuit Cash Flow Problem**
### **Objective**
Determine the smallest initial investment required to meet the court-mandated yearly cash flow payments over 15 years using available investment options.

### **Problem Summary**
- The company needs to pay specific amounts each year for 15 years as per a court's judgment.
- Available investment options include two types of bonds and a savings account with specific returns and maturity conditions.
- The goal is to minimize the initial cash required while ensuring all payments are met.

### **Approach**
- Formulated as a linear programming problem.
- Solved using Python and Gurobi to optimize the investment distribution among bonds and savings accounts.
- Output includes the optimal investment strategy and the minimal initial amount required.

---

## **2. Cancer Treatment Optimization**
### **Objective**
Optimize the radiation therapy plan to balance the damage to healthy tissues and critical areas while ensuring sufficient dosage to the tumor.

### **Problem Summary**
- Two radiation beams impact different areas of the body: tumor, healthy anatomy, and critical tissues.
- The goal is to:
  - Minimize radiation to healthy anatomy.
  - Deliver at least 6 kilorads to the tumor.
  - Limit critical tissue exposure to 2.7 kilorads.
  
### **Approach**
- Formulated as a linear programming model.
- Used Python and Gurobi to:
  1. Solve for the optimal beam intensities for the primary objective.
  2. Construct a Pareto tradeoff curve between minimizing damage to healthy anatomy and maximizing the dosage to the tumor.

---

## **Contents**
- **`Final_Code_LCFP.ipynb`**: Jupyter Notebook containing the code implementation and results for both problems.
- **`Project_Info_LCFP.docx`**: Document outlining the problem statements, constraints, and objectives.

---

## **How to Run**
1. Install the required dependencies:
   ```bash
   pip install gurobipy numpy pandas matplotlib

