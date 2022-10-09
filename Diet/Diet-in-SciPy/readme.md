# Diet in SciPy

## Summary
Description: Select foods that satisfy daily nutritional requirements at minimum cost.

Category: Diet.

Type: LP.

Library: SciPy.

Solver: HiGHS.

Source: [https://developers.google.com/optimization/lp/stigler_diet](https://github.com/glennmoy/stigler_diet)

## Notes

The model has been modified:
- The data has been extracted into a separate file.
- Method changed from 'simplex' (legacy) to use HiGHS solver.
