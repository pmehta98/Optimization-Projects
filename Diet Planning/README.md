# Starlight Meal Optimizer

This project focuses on optimizing meal plans for children in Starlight, a town facing economic challenges. Using linear programming, the project aims to design cost-effective and nutritionally balanced weekly meal plans to address food insecurity. The solutions are developed using **Python** and **Gurobi**.

---

## **Project Summary**
### **Background**
- The closure of a local factory left many families in Starlight economically vulnerable, impacting children’s nutrition.
- The "Feeding Hope" initiative, led by Principal Sally Harper, seeks to provide nutritious meals on a tight budget.
- The goal is to develop a weekly meal plan that:
  - Meets nutritional requirements.
  - Minimizes costs.
  - Ensures variety in daily meals.

---

## **Objectives**
1. Create a daily diet plan minimizing the total cost while meeting nutritional requirements.
2. Ensure no single food item exceeds 30% of the total calories or protein intake.
3. Develop a 7-day meal plan with variety and practicality for children.

---

## **Approach**
- **Formulation**:
  - A linear programming model is developed to minimize costs while adhering to nutritional constraints.
  - Variables represent servings of food items selected from a given dataset.
- **Constraints**:
  - Nutritional requirements (calories, protein, fat, vitamins, etc.).
  - Cost minimization.
  - Variety in the weekly plan.
- **Tools**:
  - Data from `food_data_diet.xlsx`.
  - Solved using Python and Gurobi.

---

## **Contents**
- **`Final_Code_Diet.ipynb`**: Jupyter Notebook containing the Python code, optimization model, and results for the problem.
- **`food_data_Diet.xlsx`**: Dataset with nutritional information and costs of food items.
- **`Project_Info_Diet.docx`**: Detailed problem description and project background.

---

## **Results**
- **Daily Plan**:
  - Optimized single-day diet plan for a child, including food item servings and total cost.
  - Adjustments made for practicality and child preferences.
- **Weekly Plan**:
  - 7-day meal plan ensuring variety and adherence to constraints.
  - Insights into the trade-offs between cost and variety.

---

## **How to Run**
1. Install the required dependencies:
   ```bash
   pip install gurobipy pandas numpy matplotlib

