# Physics-informed Machine Learning
In scientific computing, physical phenomena are often described using a strong mathematical form consisting of governing differential equations as well as initial and boundary conditions. 
PiML is a widely-used approach that integrates physical laws into ML models (for example, designing loss functions or regularization), facilitates the accurate capture of dynamic patterns and concomitantly diminishes the search space for model parameters. This approach is sometimes referred to as imposing differentiable constraints in loss functions.   It integrates (noisy) data and mathematical models, and implements them through neural networks (physics-informed neural networks) or kernel-based neural operators (physics-informed neural operators).
# Challenges of vanilla PINNs
![(a) Challenges of vanilla PINNs. (b) An example of vanilla PINNs failing to converge on high-frequency and multi-scale PDEs. 1-D convection equations with high-frequency (first row): Train and infer on a  spatial-temporary resolution 256 \times 100; 2-D steady incompressible Navier-Stokes equations (second row): Train and infer on a  spatial resolution 49 \times 77. Analytical solution and computational fluid dynamics (CFD) represent ground truth.](https://github.com/HydroPML/PaML_PiML/blob/main/fig2.png)
# The objectives and limitations of different Physics-informed Neural Networks
![image](https://github.com/HydroPML/PaML_PiML/blob/main/Table3.png)
# The objectives and limitations of different Physics-informed Neural Operators  
![image](https://github.com/HydroPML/PaML_PiML/blob/main/Table4.png)
