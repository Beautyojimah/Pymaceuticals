# Matplotlib-challenge
This repository contains a matplotlib projects for data analysis called pymaceuticals. Within the pymaceuticals folder, there is a jupyternotebook script (.ipynb) that shows the analysis of potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer in mice. 

## pymaceuticals Description
This repository contains a jupyternotebook that compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens as well as the inferenceds drawn from the analysis. 
In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens. The csv data (Mouse_metadata.csv and Study_results.csv) used for the analysis are also contained within the folder.

## Installations
Python 3.9
pandas as pd
matplotlib.pyplot as plt
scipy.stats as st
scipy.stats import pearsonr,linregress

How to run the script
clone this repo below
git clone https://github.com/Beautyojimah/Pymaceuticals.git
To run the script (pymaceuticals_solution.ipynb), cd into Pymaceuticals 

## Summary result of Analysis
The following observations or inferences are made from the data: 

- The 'Capomulin' regimen have the low mean and median tumor volumes (near 40 mm3).
  Thus,suggesting that these treatment might be more effective at reducing tumor sizes compared to the other drug regimens, whose mean and median values are notably higher (around 50-55 mm3).

- For mice treated with 'Capomulin', there is a substantial reduction in tumor volume as the timepoint increases.

- There is a positive correlation between mouse weight and average tumor volume.
