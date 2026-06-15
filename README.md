# Fluid Simulation CUDA

CUDA implementation of a 3D fluid simulation focused on exploring GPU acceleration and parallel computing techniques. The project adapts computationally intensive functions such as `lin_solve`, `diffuse`, and `advect` to CUDA kernels, using a 3D grid of threads, GPU memory management, and synchronization mechanisms.

The implementation was developed as part of a performance optimization study comparing sequential, OpenMP, and CUDA approaches.
