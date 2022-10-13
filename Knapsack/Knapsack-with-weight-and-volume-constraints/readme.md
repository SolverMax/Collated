# Knapsack with weight and volume constraints in PuLP

## Summary
Description: Select items to include in a knapsack, given weight and volume constraints.

Category: Knapsack.

Type: MILP.

Library: PuLP.

Solver: CBC.

Source: https://transport-systems.imperial.ac.uk/tf/60008_21/n3_7_knapsack_problem.html

## Notes

The notebook includes a common error:
- The model implementation has a common error that becomes apparent when we print the model using `print(prob)`.
- That is, each of the constraints is added multiple times via the `for i in S:` loop, in addition to having the sum `for i in S` in each constraint.
- The error can be corrected by removing the `for i in S:` loop.
- The model still finds the correct solution, because the extra constraints are redundant. But in a larger model this type of error may make the model more difficult to solve.
- We have retained the error to illustrate how easy it is to make this type of error, and to show how printing the model can help with debugging a model. 
