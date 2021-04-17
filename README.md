# matplotlib-challenge
Matplotlib Assignment:

This assignment analyzes data from a pharmceutical company, Pymaceuticals, that collects data from mice with squamous cell carcinoma (SCC), a common form of skin cancer.  The purpose is to screen the treament results across 10 different drug regimens with most interest in Capomulin.  This analysis includes the complete data from their animal study and generates tables and figures needed for the technical report of the study.
***
## Usage:

Jupyter Notebook file 'pymaceuticals.ipynb' reads in two csv files: 'Mouse_metadata.csv' and 'Study_results.csv' which are located in the 'data' directory.  It anaylyzes the data and outputs plots in a directory called 'plots'.  Observations on the analyzed data can be found at the top of the notebook.

MatPlotLib, Pandas, NumPy and SciPy libraries are used to generate:

- Two summary statistics tables
- Two bar plot (one using Pandas and one using PyPlot)
- Two pie plot (one using Pandas and one using PyPlot)
- Quartiles and outliers across four of the drug regimens: Capmulin, Ramicane, Infubinol and Ceftamin
- Box and whisker plot across four of the drug regimens: Capmulin, Ramicane, Infubinol and Ceftamin
- Line plot for a mouse treated with Capomulin
- Scatter plot for Capomulin treatment
- Scatter plot for Capomulin treatment with linear model added