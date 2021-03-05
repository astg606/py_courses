# Data Array Manipulation and Visualizationin Python

![NASA](http://www.nasa.gov/sites/all/themes/custom/nasatwo/images/nasa-logo.svg) ![NCCS](https://www.nccs.nasa.gov/sites/default/files/NCCS_Logo_0.png)

Data arrays are the foundation for all <a href="https://datascience.berkeley.edu/blog/python-data-science/">Data Science</a> in Python. Arrays can be multidimensional, and all the entries need to be of the same type (homogeneity).
There are several advantages of using arrays:

- Efficiently handling of very large datasets
- Computationally-memory efficient
- Faster calculations and analysis (compared to lists for instance)
- Diverse functionality (many functions in Python packages). 

There are many Python packages that make the manipulation and visualization of data
arrays easier. We intend to focus on:


- **NumPy** is the reference package for scientific computing in Python. It extends Python with a
flexible multidimensional array that allows fast and concise mathematical calculations. NumPy provides common data structures and algorithms designed to express complex
mathematical operations using a concise syntax.
- **Pandas** is a tool that relies heavily on NumPy and provides additional data structures and
algorithms targeted toward data analysis. It is best at handling tabular data sets comprising different variable types (integer, float, double, etc.). In addition, the pandas library can also be used to perform even the most naive of tasks such as loading data or doing feature engineering on time series data.
- **Xarray** introduces labels in the form of dimensions, coordinates and attributes on top of raw NumPy-like multidimensional arrays, which allows for a more intuitive, more concise, and less error-prone developer experience. The power of Xarray comes from its ability to label N-Dimensional arrays, whereas the Numpy and Pandas packages can deal with unlabelled arrays (Numpy) or labels in 2 dimensions only (Pandas). 
- **HoloViews** focuses on bundling your data together with the appropriate metadata to support both analysis and visualization, making your raw data and its visualization equally accessible at all times. With HoloViews, instead of building a plot using direct calls to a plotting library, you first describe your data with a small amount of crucial semantic information required to make it visualizable, then you specify additional metadata as needed to determine more detailed aspects of your visualization. HoloViews handles Numpy, Pandas and Xarray data arrays.


This series of presentations is best suited for people who are familiar with Python and want to acquire the basic tools necessary for Data Science in Python. 
We will learn how to manipulate different types of data arrays (Numpy arrays, Pandas DataFrames, Xarray DataArrays) and perform interactive visualization.


### [Installing the Anaconda Python Distribution](#)
It is not required to have a Python distribution installed on your local machine.
However, we believe that it is important to have one in order to write and run your own Python
applications. We recommend that you install
the Anaconda Python distribution by following the instructions at: [Anconda installation Guide](https://docs.continuum.io/anaconda/install/)

### [Installing Git](#)
To install Git on your local machine, follow the installation instructions: [Getting Started - Installing Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)


To fully follow all the topics below, you need to have a **gmail** account in order to access Google Colaboratory. Each course will be taught through the Google cloud based Jupyter notebook.


### <span style="color: red">Array Manipulation and Visualization Tools</span>

| Lecture Topic | Interactive Link | 
|:---|:---|
| **Introduction to Numpy** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/numpy/introduction_numpy_new.ipynb) |
| **Introduction to Pandas** | |
| **Interactive Data Visualization with HoloViews**  |  | 
| **Manipulating Geolocated Data with Xarray**  |  | 
| **Feedback**  | <a href="https://www.surveymonkey.com/r/BW29DG6"> Evaluation Survey </a> | 



<!---
| **Introduction to Pandas** | ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/pandas/introduction_pandas.ipynb) |
| **Interactive Data Visualization with HoloViews** | ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/visualization/introduction_holoviews.ipynb) |
| **Manipulating Geolocated Data with Xarray** | ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/xarray/introduction_xarray.ipynb) |
| 17:15-17:30 | **Feedback Session** |  |  |
| 17:15-17:30 | **Feedback Session** |  <a href="https://www.surveymonkey.com/r/PWQVXH5"> Evaluation Survey </a> | |
--->
