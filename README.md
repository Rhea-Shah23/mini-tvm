# Mini TVM: Optimizing Tensor Expression Compiler & Loop Scheduler 

A domain-specific language and optimizing compiler written in Python that decouples high-level mathematical tensor definitions from low-level execution schedules. Mini TVM compiles tensor expressions into highly optimized, cache-aware, multi-threaded C++17 kernels utilizing structural loop tiling, OpenMP parallelization, and SIMD vectorization hints. 

This project was built to demonstrate core concepts in automated compiler construction, hardware-mapping layouts, and abstract syntax tree code generation. 
