# Emerging Technologies Assignment

## Overview

This repository contains my solutions to the Emerging Technologies assessment, exploring the differences between classical and quantum algorithms. The assignment demonstrates quantum computational advantages through the implementation of Deutsch's and Deutsch-Jozsa algorithms using Qiskit.

## Repository Structure

problems.ipynb - The Jupyter notebook with all 5 problem solutions, code explanations, tests and markdown documentation.

requirements.txt - Python package dependencies required to run the notebook.

README.md - This file, providing project overview and setup instructions.

.gitignore - Makes sure that unnecessary files are removed from the repository.

## Problems Addressed

**Problem 1: Generating Random Boolean Functions** - Implementation of a random Boolean function generator that creates constant or balanced functions with 4 inputs.

**Problem 2: Classical Testing for Function Type** - Classical algorithm to determine if a function is constant or balanced, needs up to 9 function evaluations.

**Problem 3: Quantum Oracles** - Implements 4 quantum oracles in Qiskit for single-input Boolean functions used in Deutsch's algorithm.

**Problem 4: Deutsch's Algorithm with Qiskit** - Quantum circuit that determines function type with 1 test vs 2 classical tests, showing quantum advantage.

**Problem 5: Deutsch-Jozsa Algorithm** - Scales to 4-bit functions, needs 1 quantum test vs 9 classical tests. 

## Project Setup

**Clone the repository:**
```bash
git clone https://github.com/JohnsonMununkum/emerging-technologies.git
cd emerging-technologies
```

**Install Python 3.8 or higher if needed.**

**Install the required packages:**
```bash
pip install -r requirements.txt
```

Try this if pip is giving errors:
```bash
python -m pip install -r requirements.txt
```

**Run Jupyter Notebook from the project directory:**
```bash
jupyter notebook
```

**Open problems.ipynb and run the cells.** The notebook is designed to run smoothly with all imports at the top. Use **Kernel → Restart & Run All** to execute all cells in sequence.

## Key Results

- Implemented random Boolean function generator for 4-bit functions
- Classical algorithm needs up to 9 tests for 4-bit functions
- Implemented 4 quantum oracles for Deutsch's algorithm
- Deutsch's algorithm uses 1 test instead of 2 classical tests
- Deutsch-Jozsa algorithm uses 1 test instead of 9 classical tests

## Technologies Used

- **Qiskit** - Quantum computing framework for circuit design and simulation
- **NumPy** - Numerical and array operations
- **Matplotlib** - Visualization of quantum circuits and results

## Documentation

- All imports are at the beginning of the notebook
- Markdown cells explain each problem with formulas and concepts
- Code cells are commented and organized for readability
- Each problem has Solution, Operations, and References sections

