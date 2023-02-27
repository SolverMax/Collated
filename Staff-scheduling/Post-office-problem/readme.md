# Post Office problem in OR-tools CP-SAT Solver

## Summary
Description: A post office requires a different number of full-time employees working on different days of the week. Union rules state that each full-time employee must work for 5 consecutive days and then receive two days off. For example, an employee who works on Monday to Friday must be off on Saturday and Sunday. The post office wants to meet its daily requirements using only full-time employees. Minimize the number of employees that must be hired.

Category: Staff scheduling.

Type: Constraint satisfaction.

Library: OR-Tools.

Solver: CpSolver.

Source: http://www.hakank.org/or_tools/post_office_problem2_sat.py

## Notes

- Source has been converted to a Jupyter notebook.
- The original model appears to be wrong, so a constraint has been modified.
- Added an additional component to the objective function.
