# Python Tools for Accelerating and Scaling Data Science Applications on GPUs
  
![NASA](http://www.nasa.gov/sites/all/themes/custom/nasatwo/images/nasa-logo.svg) ![NCCS](https://www.nccs.nasa.gov/sites/default/files/NCCS_Logo_0.png)


Data science workflow has traditionally been slow and cumbersome when it came to loading, filtering and manipulating data, as well as ML training itself. These processes were constrained to slow, CPU-based compute, and resulted in lengthy cycle times impacting data science productivity. RAPIDS delivers GPU accelerated machine learning and data analytics libraries, deployed on NVIDIA GPU platforms, for maximized data science productivity, performance and insights. Bring the power of GPU acceleration to your research and decrease your time to new discoveries with RAPIDS.

In this course series, we will learn how to GPU-accelerate your data science applications by:

- Utilizing key RAPIDS libraries like CuPy (an implementation of NumPy-compatible multi-dimensional array on CUDA), CuDF (GPU DataFrame library that provides a pandas-like API for loading, joining, aggregating, filtering, and manipulating data.) and CuML (provides GPU versions of machine learning functions in Sckit-Learn).
- Learning how to accelerate and scale applications using Numba and Dask on both CPUs and GPUs.


**Prerequisites**: Python, Numpy, Pandas, Scikit-Learn

You might find it useful:

- To install the Anaconda Python distribution by following the instructions at: [Anaconda installation Guide](https://docs.continuum.io/anaconda/install/)
- To learn little more about Jupyter notebook: 
 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/jupyter_notebook/jupyter_notebook_introduction.ipynb)

## Materials

| Lecture Topic | Interactive Link |
|:---|:---|
| **RAPIDS CuPy, CuDF and CuML**  | [![Open In Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/rapids/rapids_packages.ipynb) |
| **Accelerating (Numba) and Scaling (Dask) Python Codes on CPUs** | [![Open In Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/rapids/numba_dask_cpus.ipynb) |
| **Accelerating (Numba) and Scaling (Dask) Python Codes on GPUs** |  |

## Additional Resources on RAPIDS

- <a href="https://rapids.ai/">RAPIDS: Open GPU Data Science</a>
- <a href="https://docs.rapids.ai/overview">RAPIDS Overview</a>
- <a href="https://cupy.dev/">CuPy: A NumPy-compatible array library accelerated by CUDA</a>
- <a href="https://github.com/rapidsai/notebooks">RAPIDS Notebooks</a>
- <a href="https://github.com/rapidsai/cuml">cuML - GPU Machine Learning Algorithms</a>
- <a href="https://github.com/rapidsai/dask-cuda">Dask CUDA</a>
- <a href="https://github.com/rapidsai/jupyterlab-nvdashboard">JupyterLab GPU Dashboards</a>
- <a href="https://developer.nvidia.com/DALI">NVIDIA Data Loading Library (DALI)</a>


<!---
| 17:15-17:30 | **Feedback Session** |  |  |
| 17:15-17:30 | **Feedback Session** |  <a href="https://www.surveymonkey.com/r/PWQVXH5"> Evaluation Survey </a> | |
--->
