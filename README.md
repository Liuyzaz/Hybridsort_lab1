# Hybrid Sorting Algorithm: Integration of Merge Sort and Insertion Sort

## Overview
This project is a lab group project under NTU course SC2001 ALGORITHM DESIGN AND ANALYSIS. It explores a hybrid sorting algorithm that integrates **Merge Sort** and **Insertion Sort** to improve efficiency when dealing with small-sized subarrays. The algorithm switches to **Insertion Sort** when the size of a subarray falls below a threshold value \( S \), minimizing the overhead of recursive calls in Merge Sort.

---

## Key Components

### 1. Algorithm Implementation
- Designed and implemented the hybrid sorting algorithm.

### 2. Input Data Generation
- Generated datasets of random integers with sizes ranging from **1,000 to 10 million**.

### 3. Performance Analysis
- Conducted empirical analysis of:
  - **Time complexity**: Measured key comparisons across different input sizes.
  - **Threshold \( S \)**: Determined the optimal \( S \) for best performance.
- Plotted results for:
  - Fixed \( S \) with varying input sizes.
  - Fixed input size with varying \( S \).

### 4. Comparison with Standard Merge Sort
- Benchmarked the hybrid algorithm against the original Merge Sort:
  - Compared key comparisons and CPU times.
  - Utilized the optimal \( S \) obtained from performance analysis.

- **Programming Language**: Python
- **Libraries**: NumPy, Matplotlib (for data generation and visualization)

---
