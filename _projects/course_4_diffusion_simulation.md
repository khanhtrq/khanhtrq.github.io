---
title: Heat Diffusion Simulation with Parallel Programming
collection: projects
category: course_projects
---

[[Report](/files/Diffusion_Simulation_Report.pdf)] [[Github Repo](https://github.com/khanhtrq/Diffusion-Simulation-with-Parallel-Programming)]  

This project is the refinement of my capstone project for the course Parallel and Distributed Programming in Spring 2022 Semester.  

<!-- ![Visualization of diffusion process](/images/diffusion_simulation.png) -->

<div style="text-align: center;">
    <img src="/images/diffusion_simulation.png" alt="Visualization of diffusion process" width="700" />
</div>
## Summary  

Diffusion describes the spreading of quatities, such as particles and heat, from high to low area of concentration over time. The system reaches equilibrium state when it remains stable without external force. Mathematically described, Laplacian of the system equals to zero at equilibirum. There are two groups of methods to solve Laplacian equation, namely direct and iteractive. While the former is used to find the exact solution, while the latter is prefered when computational time constraint is applied. 

The project focused on simulating the heat diffusion process in two-dimensional grid, where the initial state is pre-defined. To speed up the computation time, parallel programming was utilized to simulate the diffusion process. Specifically, parallel algorithm for Gauss-Seidel method was implemented with CUDA and Open MPI, and experiments were conducted on graphic processing unit (GPU) and distributed computing system. 


## Knowledge and Skills Acquired
- Understanding of the diffusion process.  
- Understanding of parallel programming and distributed computing concepts.  
- Being able to implement parallel algorithm on GPU with CUDA and distributed system with Open MPI.  