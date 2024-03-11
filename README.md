# rPPG_TruncatedSVD

How to download the PyVHR python environment?

1) Follow the link https://github.com/phuselab/pyVHR/tree/pyVHR_CPU, and make sure you are cloning the right branch of the code, namely "pyVHR_CPU" (NOT "Master").
2) Go through the README.md file to create the environment, BUT don't use the 'pyVHR_CPU_env.yml' file to install the required packages. Instead, use the updated version  'cpu_pyvhr.yml', found in this 'rPPG_TruncatedSVD' github repository, under https://github.com/giaaisgiaa/rPPG_TruncatedSVD.
3) Open 'cpu_pyvhr.yml', and at the bottom replace the given 'prefix:' with the actual path where you cloned the pyVHR repository.

How to run the 'SVD_vs_TSVD' notebook?

5) Now that you have pyVH'R installed, you can download the "Notebook_SVD_vs_TSVD" folder and move all the content of it into the "Notebooks" folder of the already downloaded pyVHR repository.
6) Navigate in the pyVHR folder, and replace the 'methods.py' original file under 'pyVHR\BVP\methods.py' with the one provided by the current repository (still named 'methods.py'), containing the new 'cpu_LGI_TSVD' rPPG algorithm. 
7) Run the 'SVD_vs_TSVD.ipynb' notebook under the "Notebooks" folder.

## SVD vs TSVD
