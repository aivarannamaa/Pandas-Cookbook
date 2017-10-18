# Pandas Cookbook
This is the code repository for [Pandas Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/pandas-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781784393878), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
This book will provide you with clean, clear recipes, and solutions that explain how to handle common data manipulation and scientific computing tasks with pandas. You will work with different types of datasets, and perform data manipulation and data wrangling effectively. You will explore the power of pandas DataFrames and find out about boolean and multi-indexing. Tasks related to statistical and time series computations, and how to implement them in financial and scientific applications are also covered in this book.
## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
>>> employee = pd.read_csv('data/employee')
>>> max_dept_salary = employee.groupby('DEPARTMENT')['BASE_SALARY'].max()
```

Pandas is a third-party package for the Python programming language and, as of the printing of this book, is on version 0.20. Currently, Python has two major supported releases, versions 2.7 and 3.6. Python 3 is the future, and it is now highly recommended that all scientific computing users of Python use it, as Python 2 will no longer be supported in 2020. All examples in this book have been run and tested with pandas 0.20 on Python 3.6.

In addition to pandas, you will need to have the matplotlib version 2.0 and seaborn version 0.8 visualization libraries installed. A major dependence for pandas is the NumPy library, which forms the basis of most of the popular Python scientific computing libraries.

There is a wide variety of ways that you can install pandas and the rest of the libraries mentioned on your computer, but by far the simplest method is to install the Anaconda distribution. Created by Continuum Analytics, it packages together all the popular libraries for scientific computing together in a single downloadable file available on Windows, Mac OSX, and Linux. Visit the download page to get the Anaconda distribution (https://www.anaconda.com/download).

In addition to all the scientific computing libraries, the Anaconda distribution comes with Jupyter Notebook, which is a browser-based program for developing in Python, among many other languages. All of the recipes for this book were developed inside of a Jupyter Notebook and all of the individual notebooks for each chapter will be available for you to use.

It is possible to install all the necessary libraries for this book without the use of the Anaconda distribution. For those that are interested, visit the pandas Installation page (http://pandas.pydata.org/pandas-docs/stable/install.html).

## Related Products
* [TensorFlow Machine Learning Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/tensorflow-machine-learning-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781786462169)

* [Data Visualization with D3 4.x Cookbook - Second Edition](https://www.packtpub.com/web-development/data-visualization-d3-4x-cookbook-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781786468253)

* [DevOps with Windows Server 2016](https://www.packtpub.com/networking-and-servers/devops-windows-server-2016?utm_source=github&utm_medium=repository&utm_campaign=9781786468550)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
