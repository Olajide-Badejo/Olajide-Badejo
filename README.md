# Olajide Badejo

GPU kernels, parallel numerics, and compiler backends (MSc Computational Engineering).  
Germany. Open to relocation and remote. Available immediately for full time roles; valid work permit.

[LinkedIn](https://www.linkedin.com/in/olajide-badejo) | [Website](https://olajide-badejo.github.io) | olajideayomidebadejo@gmail.com

I write performance critical systems code and measure it against the best
baseline I can get my hands on, usually the vendor library or the hardware
ceiling. Every project below publishes its numbers and the harness that produced
them, because a speedup nobody can reproduce is a claim, not a result. I started
in mechanical engineering, building physical systems, and moved to computational
engineering to build the software that simulates and accelerates them.

## Selected work

- [CUDA-Kernel-Library](https://github.com/Olajide-Badejo/CUDA-Kernel-Library):
  a GEMM ladder from a 1,908 GFLOP/s naive kernel to 54,985 GFLOP/s using
  mma.sync, ldmatrix, and swizzled shared memory, which is 90% of cuBLAS in FP16
  on the same GPU, with the tensor pipe at 83% of speed of light. Each rung is a
  separate kernel with its profiler run committed.
- [MLIR-Backend-for-a-Simulated-Edge-NPU](https://github.com/Olajide-Badejo/MLIR-Backend-for-a-Simulated-Edge-NPU):
  a deep learning compiler backend lowering ONNX through custom MLIR dialects to
  a binary instruction stream for a simulated NPU. On LeNet, -O2 takes 91
  instructions to 70, 23,421 simulated cycles to 12,710, and DRAM traffic from
  339 KB to 177 KB, with output matching onnxruntime to 3e-8.
- [Parallel-Numerical-Library](https://github.com/Olajide-Badejo/Parallel-Numerical-Library):
  a C++23 library whose iterative solvers run unchanged over serial, OpenMP,
  threads, MPI, and CUDA backends and return bit identical results. Measured
  against each device's own STREAM bandwidth, 62.3 GiB/s on the CPU and
  549.7 GiB/s on the GPU, red black Gauss Seidel reaches 45.7% and 47.1% of them.
  440 configurations, reproducible end to end in 23 minutes.
- [Particle-Physics-Simulation](https://github.com/Olajide-Badejo/Particle-Physics-Simulation):
  a CUDA engine for N-body gravity and SPH fluids sustaining 17.47 TFLOP/s in
  FP32, with shared memory tiling 1.93x over the naive kernel at 200,000
  particles. Correctness is pinned by ten gates, including energy drift of
  1.33e-05 over 10,000 steps.
- [Ring-AllReduce](https://github.com/Olajide-Badejo/Ring-AllReduce):
  ring allreduce built from MPI point to point primitives, then fitted to the
  alpha beta cost model at 0.250 us per message and 305.4 ps per byte, R squared
  0.981 across 375 points. The write up is explicit about where it loses to the
  vendor collective and why.
- [Low-Power-Async-CDC-FIFO-IP](https://github.com/Olajide-Badejo/Low-Power-Async-CDC-FIFO-IP):
  a parameterized asynchronous clock domain crossing FIFO in SystemVerilog with
  gray code pointers and low power intent, proven bounded in SymbiYosys and
  swept across 60 configurations for area, power, and timing.

More repositories, including an out of tree LLVM pass framework, CPU
microbenchmarks, GPU roofline profiling, MPI collective benchmarking, and ML
experiment tooling, are on the profile.

## Skills

**Programming languages:** C++, Python, C, CUDA, SystemVerilog, Fortran, Assembly (x86-64, AArch64), MATLAB  
**GPU and HPC:** CUDA kernel optimization, tensor core programming (mma.sync, WMMA), OpenMP, MPI, pthreads and C++ threads, SIMD (AVX2, NEON), Nsight profiling, roofline and speed of light analysis  
**Compilers and hardware:** MLIR, LLVM, ONNX lowering, RTL design and formal verification (SymbiYosys), Yosys and OpenSTA flows  
**ML and frameworks:** PyTorch, torch.distributed, NumPy, pandas, experiment tracking and training diagnostics  
**Tools:** Git, CMake, Docker, Linux and WSL2, GitHub Actions, LaTeX, ANSYS, Siemens NX

## Education and experience

- MSc Computational Engineering, Ruhr-Universität Bochum, 2024 to present, current CGPA 1.9 (German scale, 1.0 best)
- BEng Mechanical Engineering, Federal University of Technology Akure, 2017 to 2023, CGPA 1.1 (German scale, 1.0 best)
- Software Engineer, Whitelegg Nigeria Limited, Lagos, 2023 to 2024
- Data Engineering Intern, Monitoring Automation, Chikki Foods Industries, Lagos, 2021

<!-- Recognition: section intentionally reserved; add awards, talks, or publications here when there is one worth a recruiter's time. -->
