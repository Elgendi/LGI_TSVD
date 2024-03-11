# LGI_TSVD (for rPPG) 

How to download the PyVHR python environment?

1) Follow the link https://github.com/phuselab/pyVHR/tree/pyVHR_CPU, and make sure you are cloning the right branch of the code, namely "pyVHR_CPU" (NOT "Master").
2) Go through the README.md file to create the environment, BUT don't use the 'pyVHR_CPU_env.yml' file to install the required packages. Instead, use the updated version  'cpu_pyvhr.yml', found in this 'LGI_TSVD' github repository, under https://github.com/giaaisgiaa/LGI_TSVD.
3) Open 'cpu_pyvhr.yml', and at the bottom of it replace the given 'prefix:' with the actual path where you cloned the "pyVHR_CPU" repository.

How to run the 'SVD_vs_TSVD' notebook?

5) Now that you have pyVHR installed, you can download the "Notebook_SVD_vs_TSVD" folder and move all the content of it into the "Notebooks" folder of the already downloaded pyVHR repository.
6) Navigate in the pyVHR folder, and replace the 'methods.py' original file under 'pyVHR\BVP\methods.py' with the one provided by the current repository (still named 'methods.py'), containing the new 'cpu_LGI_TSVD' rPPG algorithm.
7) Run the 'SVD_vs_TSVD.ipynb' notebook under the "notebooks" folder.

## SVD vs TSVD

1) Pay attention to the 'method' variable in the 'SVD_vs_TSVD.ipynb' notebook. It defines the rPPG algorithm in use, e.g. LGI, LGI_TSVD, CHROM, ... Choose the algorithm you want to use to extract BPM, changing it throughout the code! 
