# Visualization
Assorted vis-related routines and tools.

## Singularity Notes

The mayavi.sif container can be built on your host system via the command:
sudo singularity build mayavi.sif mayavi_setup.def

The container can be accessed via:
singularity shell --bind /src_dir:/cshare mayavi_1.sif
Src_dir is the path to a directory you wish to mount within the container as /cshare.
E.g., src_dir = /nobackup/nfeather

Python should be invoked via the python3 command.
