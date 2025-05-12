# Substrate Exchange in a Resorcin[4]arene-Based Supramolecular Cage

This repository contains all necessary input files, simulation setups, and analysis scripts used in our molecular dynamics (MD) and enhanced sampling (OPES) study on reversible substrate encapsulation and release in a resorcin[4]arene-based supramolecular cage.

Our simulations reveal how hydrogen bond rearrangements lead to transient pore formation, enabling substrate exchange—mimicking enzyme-like behavior in supramolecular catalysis.

---

## Requirements

- **GROMACS** version 2022.5  
- **PLUMED** version 2.9 (for OPES simulations)

---

## Contents

- `.mdp` files: Simulation parameter files (`em.mdp`, `nvt.mdp`, `npt.mdp`, `md.mdp`)  
- `.tpr` files: Precompiled run input files  
- `.gro` files: Coordinate files  
- `topol.top`: Topology file  
- `plumedbias.dat`: PLUMED input file (for enhanced sampling)

---

## Simulation Steps

1. **Download required files:**
   - Coordinate files (`.gro`)
   - Force field and topology files (`topol.top`, etc.)
   - Optionally, pre-generated `.tpr` files

2. **Generate `md.tpr`:**
   If you wish to regenerate the run input file:
  

