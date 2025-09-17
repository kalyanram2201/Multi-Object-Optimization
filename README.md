# Multi-Objective Optimization of Material Properties

The project aims at predicting and optimizing **tensile strength, impact strength, and hardness** of materials with the help of **machine learning models**.
An AI-based decision system that assists in multi-objective optimization of mechanical properties for improved material design and selection should be developed.

---


## Project Structure
```
Multi-Object-Optimization-Project
```
├── multi_object_optimization.ipynb   # Jupyter Notebook containing code for data analysis, ML models, and optimization
├── sample.csv                        # Sample dataset used for training and testing
├── requirements.txt                  # Run the project using Python dependencies
└── README.md                         # Documentation of the project
```

---

## Features
- Forecasts several material properties:
- **Tensile Properties** → Yield Strength, Ultimate Tensile Strength, Elongation  
  - **Impact Strength**  
  - **Micro Hardness**  
- Uses **Linear Regression** models.  
- Implements **Train-Test Split** and **Standard Scaling** for preprocessing.  
- Provides **R² evaluation scores** for each target variable.  
- Supports **multi-objective optimization** for balancing trade-offs between properties.  

---

## Installation
Clone the repository:
```bash
git clone https://github.com/kalyanram2201/Multi-Object-Optimization.git
cd Multi-Object-Optimization
```

Install dependencies:
```bash
pip install -r requirements.txt
```

---

## Usage
### Run Jupyter Notebook
```bash
jupyter notebook notebooks/multi_objective_optimization.ipynb
```

### Train Models
Within the notebook, you can:
- Load dataset (`tensile_df`, `impact_df`, `hardness_df`)
- Train Linear Regression models separately for each target
- Visualize **R² scores** for model performance

---

## Example Output
```
R² Scores for Each Target:

Tensile:
Yield_strength_Average_MPa: 0.26
Ultimate_tensile_strength_Average_MPa: 0.68
Elongation_Average_percent: -7.27

Impact:
Impact_Strength_Average_J: 0.79

Hardness:
Micro_hardness_Average_Hv: 0.95
```

---

## Future Scope
- Increase size of dataset to enhance generalization
- Use **Neural Networks** for intricate nonlinear relationships  
- Include **Pareto front visualization** to visualize multi-objective trade-offs  
- Roll out as a **web app** (Streamlit/Django) for live use  

---

## Contributing
Pull requests are appreciated! For significant changes, please first open an issue to discuss.  

---
