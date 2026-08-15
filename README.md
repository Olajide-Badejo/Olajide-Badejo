# Olajide Badejo

HPC and ML systems engineer (MSc Computational Engineering).  
Germany. Open to relocation and remote. Available immediately for full time roles; valid work permit.

[LinkedIn](https://www.linkedin.com/in/olajide-badejo) | [Website](https://olajide-badejo.github.io) | olajideayomidebadejo@gmail.com

I build and measure performance critical systems across the stack: CUDA kernels
tuned against vendor libraries, parallel numerical runtimes over MPI and threads,
training and inference tooling for PyTorch, and hardware adjacent work from an
MLIR compiler backend to a formally verified async FIFO IP. I started in
mechanical engineering, building physical systems, and moved to computational
engineering to build the software that simulates and accelerates them.

## Selected work

- [MLIR-Backend-for-a-Simulated-Edge-NPU](https://github.com/Olajide-Badejo/MLIR-Backend-for-a-Simulated-Edge-NPU):
  a deep learning compiler backend lowering ONNX models through custom MLIR
  dialects to a binary instruction stream for a simulated NPU.
- [Parallel-Numerical-Library](https://github.com/Olajide-Badejo/Parallel-Numerical-Library):
  a C++23 library whose iterative solvers run unchanged over serial, OpenMP,
  threads, MPI, and CUDA backends and produce bit identical results.
- [Low-Power-Async-CDC-FIFO-IP](https://github.com/Olajide-Badejo/Low-Power-Async-CDC-FIFO-IP):
  a parameterized asynchronous clock domain crossing FIFO in SystemVerilog with
  gray code pointers, low power intent, and formal verification.
- [CUDA-Kernel-Library](https://github.com/Olajide-Badejo/CUDA-Kernel-Library):
  CUDA GEMM taken from a naive baseline to tensor cores through logged profiler
  driven optimization rounds, benchmarked against cuBLAS on the same GPU.
- [Ring-AllReduce](https://github.com/Olajide-Badejo/Ring-AllReduce):
  ring allreduce built from MPI point to point primitives.
- [Particle-Physics-Simulation](https://github.com/Olajide-Badejo/Particle-Physics-Simulation):
  a CUDA engine for N-body gravity and SPH fluids, with every optimization step
  measured and correctness pinned by conservation and distribution gates.

More repositories, including an out of tree LLVM pass framework, CPU
microbenchmarks, GPU roofline profiling, MPI collective benchmarking, and ML
experiment tooling, are on the profile.

## Skills

**Languages:** C++, Python, C, CUDA, SystemVerilog, Assembly (x86-64, AArch64), MATLAB  
**GPU and HPC:** CUDA kernel optimization, OpenMP, MPI, pthreads and C++ threads, SIMD (AVX2, NEON), Nsight profiling, roofline analysis  
**ML and frameworks:** PyTorch, torch.distributed, NumPy, pandas, experiment tracking and training diagnostics  
**Compilers and hardware:** MLIR, LLVM, RTL design and formal verification (SymbiYosys), Yosys and OpenSTA flows  
**Tools:** Git, CMake, Docker, Linux and WSL2, GitHub Actions, LaTeX, ANSYS, Siemens NX

## Education and experience

- MSc Computational Engineering, Ruhr-Universität Bochum, 2024 to present
- BEng Mechanical Engineering, Federal University of Technology Akure, 2017 to 2023, First Class Honors
- Engineering Intern, Simulation and Optimization, Whitelegg Nigeria Ltd, 2023 to 2024
- Data Engineering Intern, Monitoring and Automation, Chikki Foods Industries, 2021

<!-- Recognition: section intentionally reserved; add awards, talks, or publications here when there is one worth a recruiter's time. -->
