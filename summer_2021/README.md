# Python Course for 2021 NASA Summer Interns

![NASA](http://www.nasa.gov/sites/all/themes/custom/nasatwo/images/nasa-logo.svg) ![NCCS](https://www.nccs.nasa.gov/sites/default/files/NCCS_Logo_0.png)

<a href="https://datascience.berkeley.edu/blog/python-data-science/">Python is a free, a general-purpose, and portable programming language. It is easy to use with its simple syntax and readability, which makes the code easy to understand and maintain.</a> 
Python can be extended via libraries that can be used to tackle problems in machine learning, data analysis, and beyond. It has a vast ecosystem and a dynamic user's community that make Python accessible to everyone.

The focus of this course will be on Data Science.
According to <a href="https://en.wikipedia.org/wiki/Data_science">Wikipedia</a>, **Data Science** is a "concept to unify statistics, data analysis, machine learning and their related methods" in order to "understand and analyze actual phenomena" with data. It uses techniques and theories drawn from many fields within the context of mathematics, statistics, computer science, and information science.
Because of its features, Python is one of the preferred programming languages that data scientists can use to explore and analyze their datasets.
The <a href="https://stackoverflow.blog/2017/09/14/python-growing-quickly/">growth of Python in Data Science</a> has gone hand in hand with that of Pandas, External link  which opened the use of Python for data analysis to a broader audience by enabling it to deal with row-and-column datasets, import CSV files, and much more.

This course introduces the fundamental concepts of the Python programming language. In addition, it presents Python packages (Numpy, Matplotlib, Seaborn and Pandas) used for data manipulation and visualization. This course provides the necessary foundations for Exploratory Data Analysis and Machine Learning.

The instructors are:

- Carlos Cruz (carlos.a.cruz@nasa.gov)
- Bruce Van Aartsen (bruce.vanaartsen@nasa.gov)
- Jules Kouatchou (jules.kouatchou@nasa.gov)

### Objectives
You will learn the following topics:

- Python basic syntax, variables, and types
- Conditional statements and loops
- Data structures: list, tuple, dictionary, set
- Functions and modules
- I/O with text files
- Scripting and packaging
- Numpy arrays
- Basic visualization with Matplotlib
- Web scraping
- Data manipulation (reading data file, performing statistical analysis, visualization, handling time series data) with Pandas

At the end of this course, participants will be able to write their own Python scripts to read csv files, perform data wrangling, carry out basic statiscal analysis and visualize data.

To take this course, you are expected to:

- Have a gmail account (needed to have access to Google Colaboratory). Everything will be taught through the Google cloud based Jupyter notebook.
- Have a [Github](github.com) account. Github is a web-based collaborative
  tool to discover, share and build software. You might need to share what you do with your mentor. 
- Install on your local machine the Anaconda Python Distribution. It is not required but it is highly recommended if you plan to write Python code for your project.
 We recommend that you install the Anaconda Python distribution by following the instructions at: [Anaconda installation Guide](https://docs.continuum.io/anaconda/install/)
- Install Git on your local machine by following the installation instructions: [Getting Started - Installing Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git). This is not required but highly recommended.

**Classes will take place on Mondays, Wednesdays and Fridays from 1:00 am to 4:00 pm (US EST).**

### <span style="color: red">Starting Point</span>

All the classes will be provided using Jupyter notebooks. We will be explaining the featutues of Jupyter notebooks as we move along. In case you want to learn more, click on: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/jupyter_notebook/jupyter_notebook_introduction.ipynb).

Regardless of their level of proficiency in Python, all interns are expected to take the classes on **Jupyter Notebook** and **Introduction to Git**.

| Date | Lecture Topic | Interactive Link | Instructor |
|---|---|---|---|
| June 11 | **Introduction to Git**  | <a href="https://github.com/astg606/py_materials/blob/master/git_tutorial/version_control_git.pdf">Version Control with Git</a>  |  |
|  |    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/git_tutorial/basic_git_tutorial.ipynb) | |

<!---
| June 10 | **Introduction to Jupyter Notebook**  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/jupyter_notebook/jupyter_notebook_introduction.ipynb) |
| June 10 | **Introduction to Git**  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/git_tutorial/basic_git_tutorial.ipynb) |
--->

### <span style="color: red">Introduction to Python</span>

If you have never been exposed to Python, you need to take this Introduction to Python course. In case you did some Python programming in the past and you want to assess your Python knowledge, take the following test (in less that 15 minutes and without using any help):

<center>
<a href="https://forms.gle/PTV6xFCA21NYkqfp9">Python Assessment Test</a>
</center>

**<span style="color: red">Make sure that you take this placement test (only once) by June 11 before you are allowed to take any Python class.</span>** If you have any issue with the test, please contact Jules (jules.kouatchou@nasa.gov).

If you score at least 80% then only take the **Datetime** and **I/O on Text Files** topics. Otherwise, take the entire course.



| Date | Lecture Topic | Interactive Link | Instructor |
|---|---|---|---|
| June 14 | **Running Python** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/welcome/running_python.ipynb) |  |
|  | **Data Types**  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/data_types/python_data_types.ipynb) |  |
| | **Conditional Statements**  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/conditional_logic/introduction_conditionals.ipynb) |  |
| | **Loops** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/loops/introduction_loops.ipynb) |  |
| June 16 | **Advanced Data Types** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/data_types/python_data_structures.ipynb) |  |
| | **Functions** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/functions_modules/introduction_functions.ipynb) |  |
| | **Modules** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/functions_modules/introduction_modules.ipynb) |  |
| June 18 | **I/O on Text Files** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/input_output/introduction_io_text_files.ipynb) |  |
|  | **Scripting and Packaging** | |  |

### <span style="color: red">Data Science Tools</span>

This section is more for interns who will have a Data Science related project.

| Date |  Lecture Topic | Interactive Link | Instructor |
|---|---|---|---|
| June 21 | **Introduction to Numpy** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/numpy/introduction_numpy.ipynb) |  |
|         | **Basic Visualization with Matplotlib** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/visualization/introduction_matplotlib.ipynb) |  |
| June 23 | **Introduction to Pandas**  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/astg606/py_materials/blob/master/pandas/introduction_pandas.ipynb) |  |
| June 25 | **Web Scraping**  |  |  |

We will appreciate if you could fill out the following survey:

<center>
<a href="https://forms.gle/mnYy5p2Q55i7EZrX7">Course Evaluation</a>
</center>




<!---
| 17:15-17:30 | **Feedback Session** |  |  |
| 17:15-17:30 | **Feedback Session** |  <a href="https://www.surveymonkey.com/r/PWQVXH5"> Evaluation Survey </a> | |
--->
