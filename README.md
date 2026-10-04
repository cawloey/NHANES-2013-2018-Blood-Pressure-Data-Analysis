# BIOS640 Week 4: NHANES Data Analysis
NHANES 2013–2018: Blood Pressure Data Analysis
## Overview

This repository contains assignments completed for the BIOS640 class, part of 
McGill's –Health Data Analysis Graduate Certificate. The project uses 
demographic and blood pressure data from the National Health and Nutrition
Examination Survey (NHANES) to explore data manipulation, visualization,
descriptive statistics, and reporting in R. 

## Objectives

The main objectives of this project are to:

Describe the demographic characteristics of the NHANES sample.
Summarize systolic blood pressure (SBP) measurements across survey waves.
Create customized descriptive tables and visualizations using R.
Compare demographic characteristics and SBP distributions between survey waves.
Practice reproducible data analysis and reporting using R Markdown.
Develop familiarity with GitHub for project organization.

## Repository Structure

The repository is organized by assignment week, with each assignment containing
its own data, figures, reports, and supporting files.

NHANES-2013-2018-Blood-Pressure-Data-Analysis/
│
├── BIOS640-Week3-GRAssignment/
│   ├── Data/
│   │   ├── cleaned_NHANES
│   │   ├── cleaned_nhanes_final
│   │   └── diet
│   ├── Figures/
│   │   └── [Generated figures]
│   ├── Report/
│   │   ├── BIOS640-Week3-GRAssignment-Visualization.pdf
│   │   └── BIOS640-Week3-GRAssignment-Visualization.Rmd
│   ├── .Rhistory
│   └── BIOS640-Week3-GRAssignment.Rproj
│
├── BIOS640-Week4-GRAssignment/
│   ├── Data/
│   │   └── cleaned_nhanes_final
│   ├── Figures/
│   │   └── [Generated figures]
│   ├── References/
│   │   └── nhanes-2013-2018-references.bib
│   ├── Report/
│   │   ├── BIOS640-Week4-GRAssignment-Dashboard.html
│   │   ├── BIOS640-Week4-GRAssignment-Dashboard.Rmd
│   │   ├── BIOS640-Week4-GRAssignment-HTML-Formating.html
│   │   ├── BIOS640-Week4-GRAssignment-HTML-Formating.Rmd
│   │   ├── BIOS640-Week4-GRAssignment-Report-Tables.pdf
│   │   └── BIOS640-Week4-GRAssignment-Report-Tables.Rmd
│   ├── .Rhistory
│   └── BIOS640-Week4-GRAssignment.Rproj
│
└── .gitignore
└── README.md

Reports and Outputs

Each assignment includes R Markdown source files and their corresponding 
rendered outputs.

Week 3 – Visualization: Focuses on data manipulation and the creation and 
arrangement of demographic and blood pressure in visual form.
Week 4 – Advanced reporting through customized tables, HTML formatting, and 
interactive dashboards.

## Folder Descriptions

Data: Contains the datasets used in each assignment, including the cleaned 
NHANES dataset as well as a diet-related dataset for week 3 exercise 2.

Figures: Stores figures and other visualizations generated during the analysis

References: Contains BibTeX bibliography files used to manage and cite 
references in the reports.

Report: Contains the R Markdown (.Rmd) source files and their rendered outputs,
including PDF reports, HTML documents, and interactive dashboards.

.Rhistory: Stores a history of commands entered during R sessions.

.Rproj: The RStudio project file used to open and manage each assignment's 
working environment.

.gitignore: Prevent temporary files from being committed.

README.md: Provides an overview of the repository, its objectives and its 
organization.

## Data

The analysis uses NHANES data from three survey cycles: 2013–2014, 2015–2016 and
2017–2018

The datasets include demographic variables and blood pressure measurements used 
to calculate statistical variables.

## Key R packages 

tidyverse: Data manipulation, cleaning, and visualization.
rio: Importing datasets.
here: Managing reproducible, project-relative file paths.
knitr: Generating dynamic reports and tables.
kableExtra: Formatting and customizing descriptive tables.
ggplot2: Creating statistical visualizations.
cowplot and ggpubr: Arranging and combining plots.
DT: Creating interactive data tables for HTML output.


## Author

Chloé Langevin
BIOS640 – Health Data Analysis
McGill University
