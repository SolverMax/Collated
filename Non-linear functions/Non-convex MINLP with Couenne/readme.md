# Non-convex MINLP with Couenne

Source: https://helve-blog.com/posts/python/pyomo-couenne-nonconvex-minlp/

Note that the source blog is written in Japanese.

## Situation

The article describes how to install the Couenne solver on Windows, then presents an example of solving a model using Pyomo and Couenne.

The model is a constrained, non-convex, mixed integer non-linear problem (MINLP), with the following formulation:

![image](https://user-images.githubusercontent.com/106039124/194242186-fcf9c067-137e-4349-b622-f0bb11687ee7.png)

As shown in this chart of the objective function, the global minimum is -64 at x_1, x_2 = (2, 2). There are also local minima at (1, 2) and (2, -1).

![image](https://user-images.githubusercontent.com/106039124/194242334-cfb92565-9b6b-494e-8966-6cc97117d709.png)

In the article, there is a brief discussion of specifying options to the Couenne solver. For some solvers, options can be specified directly within the Python code. However, that does not work with Couenne, so an external options file must be used. We include an example of an options file, which must be in the same folder as the program.
