# Multi-constrained, multi-knapsack problem in OR-Tools

## Summary
Description: Select items to include in multiple knapsacks, given multiple attributes of each item.

Category: Knapsack.

Type: MILP.

Library: OR-Tools.

Solver: SCIP.

Source: https://github.com/benmccloskey/Linear_programming/blob/main/Multi_Constrained_Multi_Knapsack.ipynb

## Notes

This notebook is based on an example by Google. Key differences are:
- The number of attributes is expanded from one to three.
- The variables are defined as integer (0, 1) rather than Boolean, though the result is the same.
- Google's example solves the model using two methods: SCIP MIP solver and CP-SAT solver.
