
# Emerging Technologies

**Author:** Nathan Dean  
**Student ID:** G00423489 
**Module:** Emerging Technologies  
**Academic Year:** 2025/2026

## Overview

This repository contains solutions and implementations for the Emerging Technologies module assessment. The project explores fundamental concepts in quantum computing, Boolean function analysis, and the Deutsch-Jozsa algorithm.

## Repository Structure

```
.
├── problems.ipynb          # Problem set solutions
├── requirements.txt       # Python dependencies
└── README.md             # This file
```

## Problem Set

### Problems 1–5

The notebook `problems.ipynb` contains solutions for Problems 1–5 from the assessment brief, covering:
- Classical generation and testing of constant vs balanced Boolean functions
- Qiskit quantum oracles for Deutsch's problem
- Deutsch's algorithm implemented and demonstrated in Qiskit
- A 4-bit Deutsch–Jozsa circuit built from a classical truth table oracle

**Key Concepts:**
- Boolean function classification (constant vs balanced)
- Truth table representation
- Oracle function abstraction
- Mathematical proof of correctness

**Key Functions Implemented (in the notebook):**
- `random_constant_balanced()`: Generates a random constant or balanced 4-input Boolean function
- `determine_constant_balanced()`: Classically determines whether a 4-input function is constant or balanced
- `deutsch_function_generator()`: Builds the 1-bit Deutsch oracles in Qiskit
- `deutsch_algorithm()`: Runs Deutsch's algorithm using the chosen oracle
- `build_oracle_from_truth_table()` / `deutsch_jozsa_4bit()`: Builds and runs the 4-bit Deutsch–Jozsa algorithm

## Technologies Used

- **Python 3.x**
- **NumPy**: Numerical computations
- **Jupyter Notebook**: Interactive development
- **itertools**: Combinatorial operations

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Nathan-Dean371/Emerging-Technologies.git
cd Emerging-Technologies
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter:
```bash
jupyter notebook
```

# Running the Code

Open `problems.ipynb` in Jupyter Notebook and execute cells sequentially. The notebook includes:
- Function implementations
- Verification tests
- Truth table visualizations
- Mathematical proofs