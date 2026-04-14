# Algorithms Lab Assignment 1

Python implementations of fundamental algorithms . The assignment covers different problem-solving paradigms including Divide and Conquer, Greedy Algorithms, and Dynamic Programming.

## Problems Covered

1. **Problem 1: Divide and Conquer – Merge Sort**
   - Implementation of the Merge Sort algorithm using the Divide and Conquer strategy.
   - Includes runtime analysis and visualization of Execution Time vs Input Size using `matplotlib`.

2. **Problem 2: Sorting Performance Comparison**
   - Head-to-head performance comparison between **Bubble Sort** ($O(n^2)$) and **Merge Sort** ($O(n \log n)$).
   - Generates a comparative line chart to visualize efficiency differences at scaling input sizes.

3. **Problem 3: Greedy Algorithm – Fractional Knapsack**
   - Solution to the Fractional Knapsack problem using a Greedy approach.
   - Items are sorted based on their value-to-weight ratio to maximize the total carrying value.

4. **Problem 4: Dynamic Programming – 0/1 Knapsack**
   - Solution to the classic 0/1 Knapsack problem where items cannot be broken into fractions.
   - Utilizes a 2D matrix (Memoization/Tabulation) to build the optimal solution from bottom-up overlapping subproblems.

## Prerequisites

To run this notebook, you will need Python 3 installed along with the following libraries:
- `matplotlib` (for generating graphs)
- `jupyter` (to open the notebook)

You can install the dependencies via pip:
```bash
pip install matplotlib jupyter
```

## How to Run

1. Clone or download this repository to your local machine.
2. Open your terminal or command prompt in the directory containing the file.
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `vigne_lab_assignment_1.ipynb`.
5. Run all cells sequentially to see the algorithm outputs and performance graphs.
