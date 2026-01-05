# GPU-Accelerated CNN Performance Optimization (LeNet-5)

This repository contains the final project report for a GPU-based
convolutional neural network performance optimization project.

Source code is not publicly available due to academic course policy.
This report focuses on system design decisions, performance bottlenecks,
and measured optimization results.

## Problem
Baseline CNN inference performance was dominated by convolutional layer
execution on the GPU.

## Approach
- Identified convolutional layers as the primary performance bottleneck
- Optimized CUDA kernels targeting memory access and instruction efficiency
- Applied shared and constant memory, kernel unrolling, and CUDA streams
- Used Nsight Compute and Nsight Systems for profiling and iteration

## Results
- Achieved a 52.5% improvement in end-to-end CNN throughput
- Reduced memory latency and improved kernel efficiency

## Artifacts
- Full methodology, analysis, and results are available in the attached
  project report (PDF).

