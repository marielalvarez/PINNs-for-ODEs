# Tumor Dynamics Modeling Using PINNs

- Implementing the Game theory ODE that captures the interaction between resistant and susceptible tumor cell populations.
  
$$ W(i) = \sum p_j \cdot \text{Payoff}(ij) = 1 - r_i - d_i + (1 - p_i) \cdot X_i $$
$$ \overline{W} = \sum p_i \cdot W(i) $$
$$ \frac{dp_i}{dt} = p_i \left(W(i) - \overline{W}\right) $$

- Incorporating biological insights, such as fitness costs, treatment impacts, and population dynamics.
- Using Runge-Kutta numerical method to establish reference solutions.
- Solving the system with PINNs and assessing their accuracy comparing with linearization.

For more information on tumor modeling: [A Review of Mathematical Models for Tumor Dynamics and Treatment Resistance Evolution of Solid Tumors](https://pmc.ncbi.nlm.nih.gov/articles/PMC6813171/)

