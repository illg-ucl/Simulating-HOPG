# Summer student project - 2020
## Project: Simulating Brownian motion of trapped microparticles in fluid and simulating magnetic control

### Background
Graphite is a cheap material with many potential applications due to its useful electrical, magnetic, thermal and optical properties. 
For micrometer-sized particles in a static aqueous solution, the generation of particle motion requires that large, dominant viscous drag forces are overcome. 
The preferred method of generating motion is through a magnetic field gradient acting on the particle. 
Since HOPG microparticles are diamagnetic, they are attracted to magnetic field minima and can thus be trapped and made to follow minimum-field paths at a distance from the field source. 
This can be exploited for various applications, such as those in lab-on-a-chip devices. 

### Project plan
- Learning to solve differential equations computationally via Euler's method (iterative method).
- Simulating for spherical particles in different conditions by solving the differential equations of motion via Euler's method. Analysis of results. 
- Simulating for non-spherical particles in diamagnetic traps, simulating magnetic control.
  
### Jupyter notebooks
- **"Euler's Method.ipynb"**: explores the use of Euler's iterative Method to accurately solve an ordinary differential equation. Explores the step size of calculations and computation time.
- **"Brownian Motion.ipynb"**: simulates Brownian motion for a spherical microparticle. First simulates in 1D and 2D (no trapping), and does analysis of the mean square displacements. Then simulates in a 3D harmonic potential trap (like optical tweezers). Then solves in 2D in an egg-carton potential.
- **"Egg-Carton Potential.ipynb"**: definition and plot of egg-carton potential.
- **"HOPG_Magnetic_Transport.ipynb"**: simulates magnetic control of ellipsoidal graphitic microparticles (HOPG) in aqueous solution.

Example:

<p align="center">
  <img src="https://github.com/illg-ucl/Simulating-HOPG/blob/master/Brownian_project.png" width=70% height=70%>
</p>
