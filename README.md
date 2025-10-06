# 🚀 Optimization Projects Repository

![GitHub last commit](https://img.shields.io/github/last-commit/pmehta98/Optimization-Projects)
![GitHub repo size](https://img.shields.io/github/repo-size/pmehta98/Optimization-Projects)
![GitHub stars](https://img.shields.io/github/stars/pmehta98/Optimization-Projects?style=social)

## 📋 Table of Contents
- [Overview](#overview)
- [Projects](#projects)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Repository Structure](#repository-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 📌 Overview

Welcome to the **Optimization Projects Repository**! This repository showcases a collection of diverse optimization problems solved using **Python** and **Gurobi**. Each project demonstrates the application of mathematical optimization and data analytics to tackle real-world challenges across healthcare, food services, production planning, and finance.

---

## 📁 Projects

### 🏥 BCWH Scheduling

- **Folder:** [`BCWH Scheduling`](./BCWH%20Scheduling)
- **Objective:** Design an optimal shift schedule for pediatricians at BC Women's Hospital
- **Optimization Type:** Staff scheduling, constraint satisfaction
- **Key Features:**
  - Balances hard constraints (coverage, availability)
  - Soft constraints (fairness, workload distribution)
  - Simulates infeasibility scenarios
  - Provides actionable recommendations

### 🌯 Burrito Optimization Game

- **Folder:** [`Burrito Optimization Game`](./Burrito%20Optimization%20Game)
- **Objective:** Maximize profits by optimizing burrito truck placement and demand allocation
- **Optimization Type:** Location optimization, demand allocation
- **Key Features:**
  - Predictive analytics for demand estimation based on distance
  - Truck capacity constraint scenarios
  - Strategic placement analysis
  - Revenue maximization strategies

### 🍎 Diet Planning

- **Folder:** [`Diet Planning`](./Diet%20Planning)
- **Objective:** Develop cost-efficient and nutritionally balanced meal plans for children
- **Optimization Type:** Multi-objective optimization, linear programming
- **Key Features:**
  - Ensures daily and weekly dietary variety
  - Meets nutritional requirements
  - Cost minimization
  - Trade-offs between cost and nutrition quality

### 🪑 Flair Furniture Optimization

- **Folder:** [`Flair Furniture`](./Flair%20Furniture)
- **Objective:** Maximize profit margins for furniture production with quantity discounts
- **Optimization Type:** Production planning, profit maximization
- **Key Features:**
  - Evaluates production strategies for tables and chairs
  - Quantity discount modeling
  - Baseline vs. discount-optimized solutions
  - Resource allocation optimization

### 💸 Lawsuit Cash Flow Problem

- **Folder:** [`Lawsuit Cash Flow`](./Lawsuit%20Cash%20Flow)
- **Objective:** Minimize initial investment required to meet 15-year cash flow obligations
- **Optimization Type:** Financial planning, investment optimization
- **Key Features:**
  - Long-term financial planning
  - Cash flow matching
  - Investment portfolio optimization
  - Risk management strategies

---

## ✨ Features

- **Diverse Applications:** Healthcare, food services, nutrition, manufacturing, finance
- **Mathematical Optimization:** Linear programming, integer programming, constraint satisfaction
- **Real-World Scenarios:** Practical problems with realistic constraints
- **Python + Gurobi:** Industry-standard optimization tools
- **Comprehensive Analysis:** Detailed problem formulation and solution analysis
- **Sensitivity Analysis:** What-if scenarios and trade-off analysis

---

## 🛠️ Setup

### Prerequisites

- Python 3.8 or higher
- Gurobi Optimizer (academic or commercial license)
- Jupyter Notebook
- pandas, numpy for data manipulation

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/pmehta98/Optimization-Projects.git
   cd Optimization-Projects
   ```

2. **Install Gurobi:**
   - Download from [Gurobi website](https://www.gurobi.com/)
   - Follow installation instructions
   - Obtain and activate license

3. **Install Python packages:**
   ```bash
   pip install gurobipy pandas numpy matplotlib jupyter
   ```

4. **Navigate to a project:**
   ```bash
   cd "BCWH Scheduling"
   ```

---

## 📖 Usage

1. Navigate to desired project folder
2. Open Jupyter notebook:
   ```bash
   jupyter notebook
   ```
3. Run the optimization model
4. Review results and sensitivity analysis
5. Modify parameters to explore different scenarios

**Example:**
```bash
cd "Diet Planning"
jupyter notebook diet_optimization.ipynb
```

---

## 📂 Repository Structure

```
Optimization-Projects/
│
├── BCWH Scheduling/
│   ├── README.md
│   ├── scheduling_model.ipynb
│   └── data/
│
├── Burrito Optimization Game/
│   ├── README.md
│   ├── burrito_optimization.ipynb
│   └── data/
│
├── Diet Planning/
│   ├── README.md
│   ├── diet_model.ipynb
│   └── data/
│
├── Flair Furniture/
│   ├── README.md
│   └── furniture_optimization.ipynb
│
├── Lawsuit Cash Flow/
│   ├── README.md
│   └── cashflow_optimization.ipynb
│
└── README.md
```

---

## 🔧 Technologies Used

- **Programming:** Python
- **Optimization Solver:** Gurobi Optimizer
- **Data Analysis:** pandas, numpy
- **Visualization:** matplotlib, seaborn
- **Development:** Jupyter Notebook
- **Optimization Techniques:**
  - Linear Programming (LP)
  - Integer Programming (IP)
  - Mixed Integer Programming (MIP)
  - Constraint Satisfaction Problems (CSP)

---

## 🤝 Contributing

Contributions are welcome! If you'd like to add new optimization projects:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/NewOptimization`)
3. Commit your changes (`git commit -m 'Add new optimization project'`)
4. Push to the branch (`git push origin feature/NewOptimization`)
5. Open a Pull Request

---

## 📄 License

This repository is for educational and portfolio purposes. Gurobi license required for commercial use.

---

## 📧 Contact

**Pranav Mehta**

- GitHub: [@pmehta98](https://github.com/pmehta98)
- Repository: [Optimization-Projects](https://github.com/pmehta98/Optimization-Projects)

---

⭐ If you find this repository helpful, please consider giving it a star!

---
