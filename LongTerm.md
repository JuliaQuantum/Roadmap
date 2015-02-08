Let us document some key words for JuliaQuantum projects. Comment below if anything is missing or categorized badly or improper.  Features have been implemented should also documented here. Details can be discussed in particular projects. I try to make a long wishlist in case people from different areas want to implement them in Julia. 

Note: the first two parts are the foundation to other parts. Ideally, both symbolic and numerical methods should be implemented. Necessary visualization methods should also be implemented, but we ignore these kind of details in the following roadmap. 

1. Representations:
    
    1. General quantum states (see [QuBase.jl](https://github.com/JuliaQuantum/QuBase.jl)).
        - [x] Pure states (ket & bra).
        - [ ] Ensemble of quantum states.

    2. Operators (see [QuBase.jl](https://github.com/JuliaQuantum/QuBase.jl)).
        - [ ] Hamiltonian (Hermitian or non-Hermitian).
        - [ ] Evolutionary operators.
        - [ ] Functions of operators.
        - [ ] Anti/Commutators.
        - [ ] Density operators
            - [ ] Trace.
            - [ ] Coherence.
        - [ ] Superoperators.
            - [ ] Kraus operators.
        - [ ] Graph/cluster states.
        - [ ] Matrix product states and tensor networks.
        - [ ] Group and representation theory.
            - [ ] SU(2) group, Pauli group and Bloch vectors.
            - [ ] Stabilizer group.
            - [ ] Other/general SU(d) groups.
            - [ ] Coupling and span of Hilbert spaces (direct product and sum of Hilbert spaces).
            - [ ] Irreducible representations.
            - [ ] Harmonics.
            - [ ] Polar/singular value/spectral/Schmidt decompositions. 
            - [ ] Fourier transform.
    3. Coherent states and infinite dimensional space (see [QuBase.jl](https://github.com/JuliaQuantum/QuBase.jl)).
        - [ ] Squeezed states and squeezing operators.
        - [ ] Displacement operators.
    4. Wigner function, Q-function, P-function and other quasi-probability functions (see [QuBase.jl](https://github.com/JuliaQuantum/QuBase.jl)).
        - [ ] Characteristic functions.
    5. Pictures (see [QuBase.jl](https://github.com/JuliaQuantum/QuBase.jl)).
    6. Quantization of fields.

2. Quantum dynamics:

    1. Schrodinger equations.
    2. Heisenberg equations.
    3. Master equation and open quantum systems.
        - [ ] Lindblad form.
        - [ ] Bloch-Redfield form.
        - [ ] Steady-state solver.
        - [ ] Floquet formalism.
        - [ ] Non-Markov process solver.
    4. Optical Bloch equations.
    5. Heisenberg- Langevin equations.
    6. Iinput-output formalism.
    7. Quantum Monte Carlo method and quantum trajectories.
    8. Stochastic differential equations
        - [ ] Fokker-Planck equations.
        - [ ] Gaussian and other forms of noise.
    9. Perturbation theory.
        - [ ] Degenerate/non-degenerate cases.
        - [ ] Time-dependent/independent cases.
        - [ ] Adiabatic quantum evolution (population trapping, Dark states...)
    10. Green function method and many-body systems.
    11. Path integrals.
    12. Dirac equations.

3. Quantum measurement and control.
    1. Projective/von Neumann measurements.
    2. POVM.
    3. Spectrum theory.
    4. Quantum tomography.
        - [ ] State tomography.
        - [ ] Process tomography.
        - [ ] Quantum inference.
        - [ ] Quantum causality tomography.
        - [ ] tomography of quantum fields.
    5. Quantum compress sensing.
    6. Quantum parameter estimation.
    7. Quantum continuous variables and measurements.
    8. Quantum dynamic control.
        - [ ] Optimal control.
        - [ ] Feedback/feedforward quantum controls.
        - [ ] Quantum amplifier and other devices.

4. Quantum Information and computation.
    1. Information measures.
        - [ ] Amount of information:
            - [ ] Shannon entropy.
            - [ ] Relative/mutual/marginal entropy.
            - [ ] Fisher information.
        - [ ] Distance measurements.
            - [ ] Trace distance.
            - [ ] Fidelity.
        - [ ] Accessible information and channel capacity.
    2. Entanglement.
        - [ ] Entanglement measures.
        - [ ] Distillation.
        - [ ] Dilution.
    3. Computational complexity.
    4. Quantum circuit model simulations.
        - [ ] Implementations of quantum gates.
    5. Quantum random walk and quantum simulations.
    6. Topological and measurement based quantum computing.
        - [ ] Anyons and topological particles.
        - [ ] Topological orders.
    7. Quantum error correction
        - [ ] Decoherence and error channels (representation and simulations).
            - [ ] Bit/phase flip channels.
            - [ ] Depolarization channels.
            - [ ] Amplitude damping.
            - [ ] Phase damping.
        - [ ] Quantum Hamming bound and related.
        - [ ] Error correction codes (circuit generators).
    8. Fault-tolerant quantum computing analysis.
    9. Quantum algorithms simulations.
        - [ ] Quantum Fourier transform.
        - [ ] Classical simulation of other quantum algorithms.
    10. Quantum communication and quantum key distribution.
    11. Qbism and Bayesian theory.
    12. Relativistic quantum information (communication).

5. Database, coefficients and special functions for quantum.
    1. Clebsch-Gordan coefficients.
    2. 3-j and 6-j symbols.
    3. Atomic/molecular spectral and property database (from NIST and the like).
    4. Delta functions (maybe useful for symbolic calculations).

6. Other advanced topics:
    1. Quantum chemistry:
        - [ ] Computational chemistry:
            - [ ] Molecule dynamics/first-principle calculations.
            - [ ] Monte Carlo simulations.
        - [ ] Quantum computing in chemistry.
    2. Condensed matter physics. 
        - [ ] BECs, superconductors, quantum liquid and other extreme states of matter.
        - [ ] Mesoscopic physics.
        - [ ] Semiconductor and other special materials.
        - [ ] Nanophotonics and low-dimensional phenomena. 
        - [ ] Excited states and luminescence.
        - [ ] Quasi-particles and many-body systems.
    3. Atomic physics:
        - [ ] Optical lattice.
        - [ ] Laser trapping/cooling and optical molasses.
        - [ ] Ions and spin chain systems.
        - [ ] Atomic chips.
    4. Other topics on quantum and nonlinear optics:
        - [ ] Cavity/circuit-QED.
        - [ ] Interferometers, beam splitters and other devices.
        - [ ] Linear optics for quantum computing.
        - [ ] Nonlinear quantum optics and nonclassical light.
    5. High energy and particle physics.