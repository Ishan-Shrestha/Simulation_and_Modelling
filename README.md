# Simulation and Modelling

A comprehensive repository containing all laboratory work for the **Simulation and Modelling** course. This project includes practical implementations of various simulation techniques and modelling concepts using Python.

## Table of Contents

- [Overview](#overview)
- [Repository Structure](#repository-structure)
- [Labs](#labs)
- [Setup & Installation](#setup--installation)
- [How to Use](#how-to-use)

## Overview

This repository documents the progression through the Simulation and Modelling course, featuring hands-on laboratory assignments that cover fundamental concepts in computational simulation and mathematical modelling. Each lab builds upon core simulation principles and provides practical experience with numerical methods.

## Repository Structure

```
Simulation_and_Modelling/
├── README.md                          # This file
├── Generation_of_Random_Number/       # Lab 2: Random number generation
│   └── lab-2.ipynb
└── Simulation_of_Chemical_Reaction/   # Lab 1: Chemical reaction simulation
    ├── lab-1.ipynb
    ├── lab-1.md
    ├── industrial_reactor_log.txt
    └── output.txt
```

## Labs

### Lab 1: Simulation of Chemical Reaction
**Directory:** `Simulation_of_Chemical_Reaction/`

Simulates and models chemical reactions in an industrial reactor system.

**Contents:**
- `lab-1.ipynb` - Jupyter notebook with implementation and results
- `lab-1.md` - Documentation and analysis of the simulation
- `industrial_reactor_log.txt` - Input data from reactor logs
- `output.txt` - Generated simulation output

**Topics:** Reaction kinetics, reactor modeling, numerical integration

---

### Lab 2: Generation of Random Number
**Directory:** `Generation_of_Random_Number/`

Explores various methods for generating and validating random numbers for simulations.

**Contents:**
- `lab-2.ipynb` - Jupyter notebook with random number generation techniques

**Topics:** Random number generation, statistical validation, probability distributions

---

## Setup & Installation

### Prerequisites
- Python 3.7+
- pip

### Installation Steps

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd Simulation_and_Modelling
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate    # On Windows: venv\Scripts\activate
   ```

3. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   
   Common packages used:
   - `jupyter` - For running Jupyter notebooks
   - `numpy` - Numerical computing
   - `matplotlib` - Visualization
   - `scipy` - Scientific computing

## How to Use

### Running Jupyter Notebooks

1. Activate the virtual environment (if not already active):
   ```bash
   source venv/bin/activate    # On Windows: venv\Scripts\activate
   ```

2. Start Jupyter:
   ```bash
   jupyter notebook
   ```

3. Navigate to the desired lab directory and open the `.ipynb` file

### Running Individual Labs

Each lab can be explored independently:

```bash
# To run Lab 1
cd Simulation_of_Chemical_Reaction
jupyter notebook lab-1.ipynb

# To run Lab 2
cd Generation_of_Random_Number
jupyter notebook lab-2.ipynb
```

## Learning Path

Follow the labs in order for a structured learning experience:
1. **Lab 1** - Start with chemical reaction simulation to understand basic modelling concepts
2. **Lab 2** - Build on fundamentals with random number generation techniques

---

**Last Updated:** 2026-06-21
