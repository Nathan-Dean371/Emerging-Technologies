
# Emerging Technologies

**Author:** Nathan Dean  
**Student ID:** G00437021  
**Module:** Emerging Technologies  
**Academic Year:** 2024/2025

## Overview

This repository contains solutions and implementations for the Emerging Technologies module assessment. The project explores fundamental concepts in quantum computing, Boolean function analysis, and the Deutsch-Jozsa algorithm.

## Repository Structure

```
.
├── problems.ipynb          # Problem set solutions
├── project.ipynb          # Main project implementation
├── requirements.txt       # Python dependencies
└── README.md             # This file
```

## Problem Set

### Problem 1: Generating Random Boolean Functions

Implementation of a function generator that creates random constant or balanced Boolean functions with 4 inputs.

**Key Concepts:**
- Boolean function classification (constant vs balanced)
- Truth table representation
- Oracle function abstraction
- Mathematical proof of correctness

**Functions Implemented:**
- `random_constant_balanced()`: Generates a random constant or balanced function
- `is_constant_or_balanced()`: Verifies function classification

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