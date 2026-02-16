# Rayleigh-Taylor Instability in Stellar Interiors - Course Project Plan

This plan outlines a simplified study of the Rayleigh-Taylor instability (RTI) in the context of core-collapse supernovae, where heavy elements mix with lighter elements due to an unstable density inversion. The goal is to understand how this instability might influence observable features in supernova remnants.

---

## 1. Astrophysical System & Observations

### System
- **Core-Collapse Supernova:**  
  In a supernova, the inner heavy elements push into the outer, lighter hydrogen/helium envelope, creating a condition for RT instability.

### Observations
- **Spectra:**  
  Look for signatures of heavy elements (e.g., iron, nickel) in supernova remnants.
- **Images:**  
  Observe filamentary or “finger-like” structures in remnants from telescopes like Hubble.
- **Light Curves:**  
  Time variations in brightness can hint at energy transport affected by mixing.

---

## 2. Scientific Puzzle

### Key Questions
- How does the RT instability contribute to mixing heavy elements with lighter material?
- Can the simulated mixing patterns help explain observed features (e.g., spectral line shapes, remnant structure)?

### Objective
- Compare simple simulation results with available observational data to gain insight into the mixing processes in supernovae.

---

## 3. Problem Nature & Equations

### Nature
- **Time-Varying Problem:**  
  The instability starts from small perturbations and grows over time.

### Governing Equations (Simplified)
- **Hydrodynamics:**
  - **Euler Equations:** Describe the fluid motion.
  - **Continuity Equation:** Ensures mass conservation.
  - **Energy Equation:** Tracks internal energy changes.


---

## 4. Approach & Methods

### Methods
- **Analytical:**  
  - Perform a basic linear stability analysis to estimate the growth rate of the instability.
- **Numerical:**  
  - Use a simple 2D simulation (e.g., finite-volume method or lattice Boltzmann method) implemented in Python with NumPy and Matplotlib.
  
### Tools
- **Programming:** Python
- **Libraries:** NumPy, SciPy, Matplotlib

---

## 5. Project Milestones

1. **Background Research:**
   - Review literature on RT instability in supernovae.
   - Understand basic fluid dynamics equations (Euler, continuity).

2. **Develop a Simple Simulation:**
   - Write code to simulate a 2D fluid with a heavy-over-light layer.
   - Implement a small perturbation to initiate the instability.

3. **Run Simulations and Analyze:**
   - Vary parameters like density contrast and gravity.
   - Visualize how the instability grows and mixing develops.

4. **Compare with Observations & Report:**
   - Relate your simulation findings to observed features in supernova remnants.
   - Prepare a short report or presentation summarizing your methods, results, and conclusions.

---