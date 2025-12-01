# Extended Newsvendor Optimization Model  
A nonlinear optimization project integrating LP/QP modeling, price-dependent demand, and bootstrap analysis.

## 📌 Project Summary
This project builds and analyzes several extensions of the classical newsvendor model to make production decisions under uncertain demand. The work incorporates:
- Rush-printing and disposal costs  
- Price-dependent demand via linear regression  
- Joint price–quantity optimization using a quadratic program  
- Scenario-based simulation using regression residuals  
- Bootstrap replications to assess stability of optimal decisions

The result is a complete optimization pipeline showing how price elasticity and realistic cost structures materially change optimal business decisions.

## 🧠 Technical Concepts & Skills
- **Linear Programming (LP):** Reformulating the nonlinear min(·) structure with auxiliary variables  
- **Quadratic Programming (QP):** Modeling revenue with price-dependent demand  
- **Model Reformulation:** Turning piecewise and nonlinear expressions into LP/QP-solvable forms  
- **Regression Modeling:** Fitting price → demand relationships and generating simulated scenarios  
- **Statistical Simulation:** Using residual-based demand generation  
- **Bootstrap Analysis:** Re-estimating models to evaluate robustness of price/quantity decisions  
- **Python Tooling:** Gurobi, NumPy, Pandas, Matplotlib

## 📂 Included Files
- Jupyter notebook with full implementation  
- Technical write-up summarizing methodology and results  

This project highlights optimization modeling, statistical reasoning, and simulation workflows commonly used in data-driven operations and pricing analytics.
