# Chaos Control in Dynamical Systems

*Cem Özen*

Chaotic attractors are made of a skeleton consisting of an infinite number of unstable periodic orbits.
A phase space point travelling along a trajectory in the phase space of the dynamical system spends only
short periods of time in these orbits. The purpose of chaos control is to stabilize a previously
chosen unstable periodic orbit by means of applying a small perturbation to
the system. This perturbation settles the dynamics onto a chosen periodic orbit. Control of chaos in this way opens up an interesting array of possibilities for numerous applications in magneto-mechanical systems, fluid dynamics, chemical reactions, and biological systems to name a few. 

## The Pyragas Method

One of the most well-known methods of chaos control is the Pyragas (1992) method, which is also known as the delayed feedback control method. In this approach,  unstable periodic orbits are stabilized by applying small time continuous control to a parameter of the dynamical system of interest while it evolves in continuous time. Main advantages of this method are its easiness of implementation, and effectiveness for the less unstable periodic orbits. In this notebok, I present a numerical treatment of the Duffing oscillator, and apply the Pyragas method to stabilize chosen chaotic orbits in this system.
