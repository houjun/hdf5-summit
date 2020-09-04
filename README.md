# Tuning Parallel HDF5 I/O Performance on Summit

This repository has source codes and scripts to reproduce the experiments for benchmarking parallel HDF5 I/O performance.

To download this repository, do `git clone --recurse-submodules https://github.com/houjun/hdf5-summit.git`

The code has been tested on Summit and Cori supercomputers, and requrires a parallel HDF5 library installation (`module load hdf5` on Summit and `module load cray-hdf5-parallel` on Cori) to compile.
