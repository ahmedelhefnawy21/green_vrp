# Green CVRP
Using  Gurobi, I create a small instance of the **Green Capacitated Vehicle Routing Problem (CVRP)** on a single depot (node 0) and 8 customers (nodes 1–8).  Each customer $i$ has demand $d_i$ (kg), and each vehicle has capacity $Q$ (kg), with at most $k$ identical vehicles.

## Dependencies

To run the model, you need:

- **Python** ≥ 3.9  
- **Gurobi Optimizer** ≥ 11  
  - Python API: `gurobipy`  
- **Required Python packages** (install via `pip install`):  
  - `gurobipy`  
  - `matplotlib`  – for Pareto‐front plotting (optional)  
- **Standard library modules**:  
  - `math`  
- **Development & testing**:  
  - Jupyter Notebook (for exploratory demos)  
