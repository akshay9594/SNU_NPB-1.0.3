# NAS Parallel Benchmarks (C version)
This is the C version of the NAS Parallel Benchmarks v3.3 translated by 
Seol National University(SNU). The original codes are written in Fortran.
The original codes can be found here (https://www.nas.nasa.gov/software/npb.html)
This repository contains the Serial, OpenMP and OpenCL versions of the benchmarks.

## The Benchmarks

There are in total 10 benchmarks in this suite:
### Five kernels
> - IS - Integer Sort, random memory access
> - EP - Embarrassingly Parallel
> - CG - Conjugate Gradient, irregular memory access and communication
> - MG - Multi-Grid on a sequence of meshes, long- and short-distance communication, memory intensive
> - FT - discrete 3D fast Fourier Transform, all-to-all communication

### Three pseudo applications
> - BT - Block Tri-diagonal solver
> - SP - Scalar Penta-diagonal solver
> - LU - Lower-Upper Gauss-Seidel solver

### Benchmarks for unstructured computation, parallel I/O, and data movement

> - UA - Unstructured Adaptive mesh, dynamic and irregular memory access
> - DC - Data Cube
