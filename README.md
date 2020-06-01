# A GPU Accelerated Welch PSD Estimation

This project was done for my Computational Physics course.  I had access to the Vermont Advanced Computing Core (VACC), which is equiped with 80 NVIDIA  Tesla GPUs. 

This work demonstrated that calculating PSD can be sped up dramatically using a GPU.  An open source packages Reikna was used, which is build on the foundations of PyCUDA and PyOpenCL. PSD was calculated of two real-world data-sets, those being 10 MHz of the FM radio band, and 1.6 GB of R1 gravitational wave data from LIGO Caltech. The GPU code demonstrated a speedup of 20x when compared to Scipy's welch function processing the large data set from LIGO Caltech. 
