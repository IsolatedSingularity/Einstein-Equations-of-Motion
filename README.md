# Einstein Field Equations

![alt text](https://github.com/IsolatedSingularity/Einstein-Equations-of-Motion/blob/main/Plots/Capture.PNG)

## Objective

Computation of the Einstein field equation solutions and geodesic equations for a non-vanishing energy densities and expanding spacetimes.

## Code Functionality

The code begins by setting up the Einstein field equations, which are a set of ten coupled partial differential equations. These equations relate the metric of spacetime (how distances are measured) to the distribution of energy, momentum, and stress in the universe. The code uses different metric tensors to represent various spacetime scenarios. The Ricci tensor, which is a key component in the Einstein field equations, is computed. It characterizes the curvature of spacetime and depends on the metric and its derivatives. The code computes the Ricci tensor for different metric tensors and simplifies the results. The Ricci scalar is derived by contracting components of the Ricci tensor. It represents the scalar curvature of spacetime. The code calculates the Ricci scalar for each metric. The Einstein tensor is computed by combining the Ricci tensor and Ricci scalar with the metric tensor. It encapsulates the effects of gravity in the Einstein field equations. The code then checks whether the Einstein field equations are satisfied for each metric. If the Ricci tensor is equal to the Einstein tensor, this implies that the metric solves the Einstein field equations, indicating a valid spacetime solution. The code switches focus to geodesic equations, which describe the paths of particles or objects moving freely through curved spacetime. It calculates the geodesic equations for the given metrics, which govern how the four-velocity of particles evolves along their trajectories.
