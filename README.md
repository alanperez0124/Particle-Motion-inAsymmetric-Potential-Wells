# Particle-Motion-in-Asymmetric-Potential-Wells
## Description
In this problem for my computational physics course, we consider the motion of a particle in three different potential wells. The three wells are: a double-well potential, a square/inverse-square potential, a quartic/inverse-square potential. Specifically, I used the Runge Kutta method to model the motion of the particle in the in the three wells.

## Claims we wanted to verify or refute
1. In all three cases, if a particle starts off with a velocity v = 0 at a position close to the minimum of the potential, the period of oscillation is approximately 1. 
2. In at least one of these potentials, starting the particle far from the minimum of the potential will NOT change
    the fundamental frequency of oscillation (i.e., the lowest positive frequency).
3. In at least one of these potentials, starting the particle far from the minimum of the potential will change the
    fundamental frequency of oscillations, and if the energy is “small” the shift Δ is proportional to the energy
    of the particle 𝐸. Note that you can find the frequency either by measuring the period from a plot of 𝑥(𝑡), or
    by looking at the Fourier transform. If you run the simulation for a long time, the peaks of the Fourier
    transform will be very sharp
4. In all three potentials, at low energies 〈𝑥〉 − 1 ∝ 𝐸.

## Addition to the problem
Next, we added a damping and driving force to the problem. We then wanted to verify or refute the following claims: 
1. In the absence of a driving force (for example, if you set 𝐹> = 0), if you start the particle off away from
    equilibrium the motion will be an oscillation with exponentially decaying amplitude, and the time that it takes
    for the amplitude to decay to half its initial value is inversely proportional to 𝛾.
2. In the presence of a small driving force, after an initial period of complicated motion, it will settle into a state
    of steady oscillations at the same frequency as the driving force, and with an amplitude that is proportional
    to the amplitude of the driving force.
