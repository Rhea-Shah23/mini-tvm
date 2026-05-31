# mini-tvm
Optimizing tensor expression compiler and loop scheduler built in Python. It decouples functional mathematical definitions from execution strategies, translating high-level tensor operations into multi-threaded, cache-aware C++17 kernels. Features structural loop tiling, OpenMP parallelization, and SIMD vectorization hints.
