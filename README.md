# Project-2: Automation of Concrete Mix Design

## Project Overview 
This repository contains a python based automation tool for the NDOT that calculates given concrete mix designs.

## Repository Contents 
- [Python Code](CIVE202_Spring2026_JustinWitcofski_Project2_Code.ipynb)
- [SOW and Gantt Chart](CIVE202_Spring2026_JustinWitcofski_Project2_SOW_GanttChart.pdf)
- [Mix Design Results](NDOT_Mix_Design_Results.csv)

## Python Tool User Guide

### Prerequisites
Ensure you have a Python environment installed with the following libraries imported:
- `pandas`

### Running the Automation
1. Download the `CIVE202_Spring2026_JustinWitcofski_Project2_Code.ipynb` file.
2. Open the file in Jupyter Notebook or Google Colab.
3. Go to the top menu and select Cell > Run All.
4. The script will execute the four standard NDOT mix scenarios (47B, 47BR, High Strength, and 47B-Air).

### Reviewing Results
- Output: The notebook will print a summary of Water Weight (Q), Fine Aggregate Weight (Y), and Coarse Aggregate Weight (Z) for each scenario.
- CSV Export: A file named `NDOT_Mix_Design_Results.csv` will be automatically generated in your local directory. This file can be opened in Microsoft Excel for further professional reporting.

### Customizing Mixes
To test a new mix design, locate the `scenarios` list in the second code cell and add a new dictionary entry with your specific material weights and specific gravities.

