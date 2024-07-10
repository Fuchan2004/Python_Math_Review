# Python_Math_Review

This repository hosts the files from the MIT-WHOI Incoming JP Student Summer Math Review, Introduction to Python Course. In addition you can find step-by-step instructions on this course.

The use of this repository is for MIT-WHOI JP Students and affiliates only, please contact me if you wish to use this course material.

*Created by:* Fadime Stemmer, Zoe Aarons

*Last Updated:* 07/10/2024

## Goals
* Introduction to python and programming languages in general terms
* Introduction to the python interpreter
* Introduction to conda
* Setting up jupter notebook on the HPC
* Survey of terms and data types in python
* Operators in python
* Lists, dictionaries, sets
* Libraries and modules
* For loops!

## Why Python?
Python is an open source, object-oriented programming language with useful applications in data science, numerical modeling, GIS, and developing open source software. Other than Python there are a variety of programming languages that can be used. For science you can use whatever suits your work. Popular choices include:
* Python
* Pearl
* R
* Matlab
* C/C++

Once you master one programming language, it is much easier to learn the next. Python is particularly beginner friendly due to the simple syntax while allowing you to go through complex tasks, and is thus a popular first programming language. 

Python is:
* Interactive
* Interpreted
* Portable
* Modular
* Object-oriented
* Open access
* Free
* Widely used


Python has:
* An extensive (scientific) user base
* A large and varied set of support libraries
* Good system of scalable tools (e.g. Pangeo)
* Good scientific notebook style interactive interface (Jupyter)

## Running the Python interpreter 

## Jupyter Notebooks
Jupyter (a mash up of Julia-Python-R) is a pen-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. The power of Jupyter is that it can be set up to run any number of code interpreters. This can be done by selecting a different "kernel". These notebooks can be shared, downloaded, posted to websites, turned into pdfs... the options are basically endless. They can even be viewed on Github! `jupyter notebooks` are interactive and easily readable interphases for running and visualizing code and keeping notes such as Python and R. Notably, code and output graphics or answers are tightly linked together rather like a laboratory notebook. Jupyter notebooks act as a GUI interface of sorts to run python code. Yet, they are saved as convenient chunks of code (ending in .ipynb) that can be opened again, re-run, shared, and modified.

### Anaconda
Anaconda is used to run and manage `jupyter notebooks`. It is a free and open-source distribution of the Python and R programming languages for scientific computing. Through the function `conda` Anaconda facilitates the installation of python and R programming languages as well as packages. It is a great tool for ensuring that computational environment is associated with code and really streamlines program installation and use. 
* Package and libraries manager for many languages (Python, R, Java, C/C++, etc.)
* Download includes most recent version of Python & relevant libraries (numpy, pandas, etc.)
* Navigator application
* Connections with associated software (Jupyter, Spyder, RStudio, etc.)

### Opening Jupyter Notebooks
To run jupyter notebooks on a local computer type `jupyter notebook` in your terminal. It will automatically open the browser to run jupyter notebooks.
Prior to this class we asked you to download the 2024_Python_Math_Review folder on your computer. By going to terminal and opening jupyter notebook from this folder, you will reach following page displaying the contents of the folder within jupyter. 

<img width="1153" alt="Screenshot 2024-07-10 at 07 23 39" src="https://github.com/Fuchan2004/Python_Math_Review/assets/139340364/f0a348cc-13dc-45f1-a54b-b1dd091d1e8e">

The screen you see is called the home screen or dash board. This should show you a navigable file structure much like what you might find on your computer. In our folder we can find files ending on `.ipynb` which are our jupyter notebooks containing the code we will work with today. For detailed information on how to design and organize your jupyter notebook, check out following resource on shortcuts for markdowns: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

To start a new notebook. Go over to New drop down menu and select Python or the like. This is going to open up a new Jupyter Notebook within our special conda environment for us to work within.

> Quick tip: if you are lost or confused just type H (while not in a cell). This brings up a handy cheat sheet.
You should now see a new Jupyter Notebook window.

**Now lets get started with the actual coding!**

## Python 
### Terms and Data Types
#### General Terminology
| Term        | Definition           |
| ------------- |:-------------:|
| Arguments     | Values given to a program when it is run |
| Code      | Program or or portion of program; Act of writing a program   | 
| Execute | To begin to run a program (see also: run) |
| Function |A subprogram that can be called to run the same task |
|Parameters | Values given to a function |
| Return | The act of sending back a value as part of a function |
| Variable | A name that holds a value |

#### Basic Data Types
|Type	| Example |
| ------------- |:-------------:|
|Integer	| A whole number; e.g. 85, 0 |
|Float	| Any number (scientific, decimal); e.g 3.14, 4.2e-10 |
|Boolean |	Binary True/False |
|String	| A collection of text characters (numbers, letters, etc.); e.g. "Homo sapiens", "33" |

#### Mathematical Operations
|Symbol | Example |
| ------------- |:-------------:|
|+	|Addition|
|-	|Subtraction|
|*	|Multiplication|
|/	|Division|
|**	|Power/exponent|
|%	|Modulo|
|//	|Truncated division (without remainder)|

#### Comparative and Logical Operators
|Symbol	|Example|
| ------------- |:-------------:|
| `==` |	Equals|
|`!=`	| Does not Equal |
|`>, >=`	| Greater than |
|`<, <=`	| Less than |
|`and, &	`| And |
| `or, |`	| Or |
| `not, !`|	Not |

### Variables
Unlike some other programming languages, you do not need to specify what a variable is going to be. It can honestly be anything and will take on anything. Any data type can be assigned to a variable with the `=`. For example:

```python
my_name = 'Poseidon'
blue = 'red'
apple = 5
```

You can print the value of a variable with the command `print()`:

```python
print(my_name)
```










