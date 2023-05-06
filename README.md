# Exam Results Jupyter
A project I made back in 2021! Plots graphs using csv data.
###
<img src="https://github.com/hamdivazim/ExamResultsJupyter/raw/main/screenshot.png">

## Prerequsites
You will need:
* `numpy`
* `pandas`
* `seaborn`
* `matplotlib`
* IPYNB Kernel

## What does it do?
Using `ExamResults.csv` (which by the way you can play around with), this Jupyter Notebook generates 4 bar charts using `matplotlib` and a line graph (`'catplot'`) using `seaborn`. At the start, it also uses `pandas` to add two new columns to the table it generates from the `csv`: 'Pass/Fail' which is determined by overall mark and current year/grade, and 'Grading', which is one of `['F', 'C', 'B', 'A', 'A*']` based on overall mark.
