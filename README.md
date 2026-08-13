# A Neural ODE Model for Temporal Molecular Concentrations

A neural ordinary differential equation (neural ODE) model is developed to learn the dynamics from the time-dependent molecular concentrations of a complex biochemical system and predict an irregularly sampled continuous evolution of the system.

The state of a dynamic system can be represented in a general form as:

$$
\frac{\mathbf{d} \mathbf{h} \left( t \right)}{\mathbf{d} t} = f \left( \mathbf{h} \left( t \right), t, \theta \right)
$$
where, the time derivative of the system $\frac{\mathbf{d} \mathbf{h} \left( t \right)}{\mathbf{d} t}$ is parameterized by a neural network model $f$.
