# Tumor Dynamics Modeling Using PINNs

- Implementing the Game theory ODE that captures the interaction between resistant and susceptible tumor cell populations.
![Equation 1](https://latex.codecogs.com/svg.latex?W%28i%29%20%3D%20%5Csum%20p_j%20%5Ccdot%20%5Ctext%7BPayoff%7D%28ij%29%20%3D%201%20-%20r_i%20-%20d_i%20%2B%20%281%20-%20p_i%29%20%5Ccdot%20X_i)

![Equation 2](https://latex.codecogs.com/svg.latex?%5Coverline%7BW%7D%20%3D%20%5Csum%20p_i%20%5Ccdot%20W%28i%29)

![Equation 3](https://latex.codecogs.com/svg.latex?%5Cfrac%7Bdp_i%7D%7Bdt%7D%20%3D%20p_i%20%5Ccdot%20%5Cleft%28W%28i%29%20-%20%5Coverline%7BW%7D%5Cright%29)

- Incorporating biological insights, such as fitness costs, treatment impacts, and population dynamics.
- Using Runge-Kutta numerical method to establish reference solutions.
- Solving the system with PINNs and assessing their accuracy comparing with linearization.

For more information on tumor modeling: [A Review of Mathematical Models for Tumor Dynamics and Treatment Resistance Evolution of Solid Tumors](https://pmc.ncbi.nlm.nih.gov/articles/PMC6813171/)

