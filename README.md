# K-means Clustering Optimization using CUDA (CPU vs GPU)

This repository contains a Jupyter Notebook that implements and compares **K-means clustering** on:
- **CPU** implementation
- **GPU** implementation using **CUDA**

The goal is to evaluate how GPU parallelization improves performance for clustering workloads.

## Repository Contents

- `ParallelProgramming_K-means_CPUVSGPU.ipynb`  
  Main notebook containing code, experiments, and CPU vs GPU comparison.

## Project Objectives

- Implement K-means clustering baseline on CPU
- Implement/accelerate K-means with CUDA on GPU
- Compare execution time and performance behavior
- Discuss speedup and scalability trends

## Requirements

To run the notebook, you typically need:

- Python 3.x
- Jupyter Notebook / JupyterLab
- NumPy, Matplotlib (and any additional notebook dependencies)
- NVIDIA GPU with CUDA support
- CUDA toolkit/drivers configured on your system

> If CUDA is not available, CPU sections can still run, but GPU-accelerated sections may fail or be skipped.

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/FarisElbaz/K-means-Clustering-Optimization-using-CUDA.git
cd K-means-Clustering-Optimization-using-CUDA
```

2. Launch Jupyter:

```bash
jupyter notebook
```

3. Open:

- `ParallelProgramming_K-means_CPUVSGPU.ipynb`

4. Run cells in order to reproduce experiments and comparisons.

## Expected Output

The notebook demonstrates:
- K-means clustering workflow
- CPU runtime results
- GPU runtime results (CUDA)
- CPU vs GPU performance comparison and observed speedup

## Notes

- Results may vary by dataset size, number of clusters, GPU model, and CUDA configuration.
- For fair benchmarking, run multiple trials and average timings.

## Future Improvements

- Add reproducible environment file (`requirements.txt` / `environment.yml`)
- Include benchmark tables and plots in this README
- Add dataset documentation and experiment configuration details

## Author

- **Faris Elbaz**
