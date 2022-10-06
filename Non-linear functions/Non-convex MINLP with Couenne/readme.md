# Non-convex MINLP with Couenne

## Description
Summary: Minimize 2D polynomial with multiple local optima.

Category: Non-linear functions

Type: Non-convex MINLP

Library: Pyomo

Solver: Couenne

Source: https://helve-blog.com/posts/python/pyomo-couenne-nonconvex-minlp/ (in Japanese)

## Notes

The article describes how to install the Couenne solver on Windows, then presents an example of solving a model using Pyomo and Couenne.

There is a brief discussion of specifying options to the Couenne solver. For some solvers, options can be specified directly within the Python code. However, that does not work with Couenne, so an external options file must be used. We include an example of an options file, which must be in the same folder as the program.
