# Matrix Multiplication Using Threading

## Overview
This Python notebook demonstrates the use of threading to efficiently perform matrix multiplication. The process involves generating random matrices and their subsequent multiplication by a constant matrix, utilizing the computational power of multiple cores to expedite calculations.

## Methodology

### 1. Random Matrix Generation
- **Purpose**: Generate a large number of matrices to simulate extensive data processing tasks.
- **Implementation**: Utilize NumPy to create 500 random matrices, each of size 5000x5000. This provides a substantial amount of data for performance testing matrix operations.

### 2. Constant Matrix Production
- **Purpose**: Serve as a consistent operand for matrix multiplication across all operations.
- **Implementation**: A single 5000x5000 matrix with fixed values is generated to multiply with each of the 500 random matrices.

### 3. Threading for Matrix Multiplication
- **Purpose**: Leverage threading to improve the performance of matrix multiplication operations.
- **Implementation**: Threads are created for each multiplication task to utilize CPU cores more efficiently, reducing overall computation time.

### 4. Performance Metrics
- **Purpose**: Assess the efficiency of the threading implementation in matrix multiplication.
- **Implementation**: The performance is evaluated by scaling up the number of CPU cores and measuring the impact on processing time for matrix multiplications. This helps in identifying the optimal number of threads for maximizing computational speed.

## Requirements

- Python 3.x
- NumPy
- Threading module

## Setup and Execution

Clone the repository, navigate to the directory containing the notebook, and run it using Jupyter Notebook or JupyterLab:

```bash
git clone [[repository-url](https://github.com/ArryuannKhanna/MultiThreading_MatrixMultiplication)]
cd [repository-directory(https://github.com/ArryuannKhanna/MultiThreading_MatrixMultiplication)]
jupyter notebook
