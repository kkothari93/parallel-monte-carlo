# parallel-monte-carlo

This repository contains an implementation of Massively Parallel Monte Carlo on NVIDIA CUDA. The algorithm has been adapted from the paper by J. Anderson et al 'Massively parallel Monte Carlo for many-particle simulations on GPUs' in Journal of Comp Physics 2013. This was done as part of a course project at UIUC in the course Atomic Scale Simulations. We modified the data structure and computation mapping to achieve a bigger speedup for relatively small systems than what the paper considers. This allowed for better performance than the paper's algorithm hugely reducing computation time and utilizing higher parallelism.

The code was written and debugged in Visual Studio 2013 using the NVIDIA Toolkit 7.5
