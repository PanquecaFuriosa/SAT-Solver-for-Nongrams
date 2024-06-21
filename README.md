# SAT solver to solve Nonograms

This project is a nonogram solver that uses a graphical interface to load and solve nonograms.

## Requirements

To run this project you need to have Python 3 and the following libraries installed:
- pysat
- tkinter

You can install these libraries with pip:

```
pip install python-sat
pip install tk
```

## Clone the Repository

To get a copy of the source code, you can clone the GitHub repository using git:

```
git clone https://github.com/PanquecaFuriosa/SAT-Solver-for-Nongrams
```

## Execution

To run the project, navigate to the project directory and run the main script with Python 3:

```
cd SAT-Solver-for-Nongrams
python main.py
```

When the interface is executed, you must load a test file, for example test6.txt, in the _Load nonogram_ button and then click the _Solve nonogram_ button for the program to solve the nonogram and display the result.

## Input file

A plain text file is used to describe the problem. The file contains a single object with the following fields:

```
<no_columns> <no_rows>
<row_1>
<row_2>
...
<column_1>
<column_2>
```
Tests files are in the tests folder.
