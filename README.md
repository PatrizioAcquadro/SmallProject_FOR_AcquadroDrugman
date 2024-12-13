# Small Project: Healthcare Scheduling Optimization

This repository contains a university project for a healthcare scheduling optimization problem, for the course of "Foundations of Operational Research", from Prof. Malucelli. The objective is to assign patients to rooms and schedule nurses while minimizing total admission delays. This problem is inspired by the Integrated Healthcare Timetabling Competition 2024.

## Contents

- `test20.json`: The JSON dataset containing all the input data (days, rooms, patients, nurses).
- `AcquadroDrugman.ipynb`: The Jupyter notebook implementing the data loading, model formulation, solution, and analysis.

## How to Run

1. Launch Google Colab or a local Jupyter environment.
2. Open `AcquadroDrugman.ipynb`.
3. Ensure that you have the necessary packages installed (Gurobi, PuLP, or another MIP solver, plus `pandas`, `requests`, etc.).
4. Run all cells in the notebook to:
   - Load data from `test20.json` via the provided raw GitHub URL.
   - Formulate and solve the optimization model.
   - View the results and analysis.

## Dependencies

- Python 3.8+
- A MIP solver such as Gurobi or CBC
- `pandas` for data handling
- `requests` for loading data from a URL
- `json` for parsing the dataset

## License

This is a university project. Check with the course instructor or author for licensing information.
