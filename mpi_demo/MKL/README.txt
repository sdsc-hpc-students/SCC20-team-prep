### MPT:  10/7/2020 -- Example is not working

[1] Compile:

module purge
module load slurm
module load cpu
module load intel-mkl  mvapich2
module load openmpi/4.0.4

mpif90 -o hello_mpi hello_mpi.f90

[2] Run:

sbatch hellompi-slurm.sb

NOTE: for other compilers, replace "gcc"
with the one you want to use.
