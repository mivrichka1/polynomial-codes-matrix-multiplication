
# Distributed Matrix Multiplication with Polynomial Codes

Educational project that models distributed matrix multiplication with polynomial codes and straggler nodes.

The goal is to show how matrix blocks can be encoded as polynomial evaluations, processed by workers, and decoded from a subset of completed results.

## Stack

- Python
- NumPy
- Matplotlib

## What is implemented

- block partitioning of matrices;
- polynomial encoding of matrix blocks;
- distributed worker simulation;
- slow/straggler node simulation;
- decoding through polynomial interpolation;
- comparison with direct matrix multiplication;
- error visualization for different numbers of workers.

## Project structure

```text
polynomial-codes-matrix-multiplication/
├── README.md
├── requirements.txt
├── polynomial_codes.py
└── plots/
```

## How to run

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the experiment:

```bash
python polynomial_codes.py
```

The script prints reconstruction errors and saves a plot to `plots/reconstruction_error.png`.

## Notes

This is a simplified educational simulation. It is intended to demonstrate the core idea of polynomial codes rather than to provide an optimized distributed framework.
