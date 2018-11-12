
# CPSC817 Physically-Based Animation Course Project Proposal

Particle systems can be exploited to finish lots of amazing animation.
We learned, in the class, to use the particle system to, for example, simulate the motion of bounce balls, galaxy and boids.
The interaction between particles in these examples is relatively simple.
We plan to implement a particle system in which the interaction between particles is complicated -- **Smoothed-Particle Hydrodynamics** (SPH).


SPH is a computational method to simulate the motion of fluid.
It considers the fluid as the assembly of a batch of particles and simulate their motion as the result of external force, pressure force and visocity force, which associated with the density, pressure and velocity properties of particles.


We intend to implement SPH with two-way collision.
That is, when collision occurs, particles and an external object will apply force on each other.
Due to that the computation of SPH is complicated, its performance when running on CPU is very limited.
We plan to implement SPH on GPU using **CUDA** with millions of particles.


Some demos of SPH can be found at

[https://www.youtube.com/watch?v=Qve54Z71VYU](https://www.youtube.com/watch?v=Qve54Z71VYU)


[https://www.youtube.com/watch?v=GPZL84QrfBQ](https://www.youtube.com/watch?v=GPZL84QrfBQ)