# BinX Tech AI/ML Internship — Week 1

## Overview

This repository contains the Week 1 deliverables for the BinX Tech AI/ML Internship Program.

Week 1 focuses on Python & Data Science Foundations: setting up a professional Python
environment and building fluency in the four core libraries used throughout the program —
NumPy, Pandas and Matplotlib — all within the Jupyter Notebook workflow.

## Objectives

- Set up a reproducible Python data-science environment (venv, pip, Jupyter)
- Write clean, idiomatic Python (data types, control flow, functions, list comprehensions, OOP)
- Create, index, slice, and vectorize computations over NumPy arrays
- Load, inspect, clean, filter and aggregate tabular data with Pandas
- Produce clear, labeled visualizations with Matplotlib
- Commit well-structured, documented notebooks to GitHub

## Project Structure

binx-ai-ml-internship/
├── notebooks/
│   ├── Day1_Setup.ipynb
│   ├── Day1_README.txt
│   ├── Day2_Python_for_Data_Science.ipynb
│   ├── Day2_README.txt
│   ├── Day3_NumPy.ipynb
│   ├── Day3_README.txt
│   ├── Day4_Pandas.ipynb
│   ├── Day4_README.txt
│   ├── Day5_Matplotlib.ipynb
│   └── Day5_README.txt
├── data/
│   └── adult.csv
├── requirements.txt
└── .gitignore

## Daily Hands-On Labs

### Day 1 — Environment Setup & Jupyter Workflow
Set up a reproducible Python environment using a virtual environment and pip.

**Hands-On Lab:**
- Created and activated a virtual environment, then installed NumPy, Pandas, Matplotlib and Jupyter
- Built a notebook mixing Markdown and code cells
- Printed installed library versions to confirm the setup
- Froze the environment to `requirements.txt`
- Initialized Git and made the first commit

### Day 2 — Python for Data Science
Built fluency in core Python fundamentals used throughout the program.

**Hands-On Lab:**
- Wrote a function returning the mean, min and max of a list as a dictionary
- Rewrote a for-loop filtering even numbers as a single list comprehension
- Defined a small class representing a data record with attributes and a method
- Documented each step with Markdown explanations

### Day 3 — NumPy: Numerical Computing
Learned to create, manipulate and vectorize operations over NumPy arrays.

**Hands-On Lab:**
- Created a (4,4) array with values 1–16 and inspected its shape and dtype
- Sliced the array to extract the second column and the last row
- Used a boolean mask to select values greater than the array's mean
- Applied broadcasting to add a 1D row to every row of the array, verified manually

### Day 4 — Pandas: Tabular Data
Loaded, cleaned, filtered and aggregated a real dataset using Pandas.

**Dataset:** UCI Adult Census Income (from Kaggle)

**Hands-On Lab:**
- Loaded the dataset and reported its shape, columns and dtypes
- Detected missing values (stored as `"?"`) and handled them via mode imputation
- Filtered the data to a meaningful subset (individuals older than 50)
- Used `groupby` to compute average hours worked per week by education level

### Day 5 — Matplotlib & Week 1 Mini-Notebook
Brought together the full pipeline of Week 1: load → clean → compute → visualize.

**Hands-On Lab:**
- Produced a histogram of the age distribution
- Produced a scatter plot of age vs. hours worked per week
- Produced a bar chart of average hours worked by education level
- Interpreted each visualization in Markdown cells

## Tools & Technologies

- Python 3.10+
- venv, pip, requirements.txt
- NumPy, Pandas, Matplotlib
- Jupyter Notebook
- Git & GitHub

## Notes

Every notebook follows a report-style structure: Markdown cells explain each step, code executes
it and outputs are shown directly beneath. Missing values are handled explicitly and justified
in each notebook where relevant.

Update Week 1 README with full daily breakdown and hands-on labs.
