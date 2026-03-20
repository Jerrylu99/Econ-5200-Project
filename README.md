# ECON 5200 Midterm Project

## Project Overview
This project replicates and extends the analysis from Card and Krueger (1994), *Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania*.

The purpose of this project is to examine the effect of a minimum wage increase on employment in the fast-food industry using a Difference-in-Differences (DID) framework.

## Why This Paper
I chose this paper because it is a classic study in labor economics and one of the most well-known applications of the Difference-in-Differences method. It provides a clear example of how econometric tools can be used to evaluate public policy.

## Research Question
The main research question of the paper is whether an increase in the minimum wage reduces employment in the fast-food industry. Specifically, the study compares fast-food restaurants in New Jersey and Pennsylvania before and after New Jersey raised its minimum wage.

## Methodology
This project is divided into three parts:

### Phase 1: Data Cleaning
- Load the raw dataset into Python
- Clean and organize the data
- Save the processed dataset for later analysis

### Phase 2: Replication
- Reproduce the baseline Difference-in-Differences analysis
- Compare employment changes in New Jersey and Pennsylvania
- Interpret the estimated treatment effect

### Phase 3: Extension
- Extend the baseline DID model with an event-study framework
- Examine the dynamic pattern of treatment effects over time
- Evaluate whether the parallel trends assumption is plausible

## Data
The dataset contains information on fast-food restaurants in New Jersey and Pennsylvania.  
The raw data are stored in the `data/raw` folder, and the cleaned data are stored in the `data/processed` folder.

## Repository Structure
```text
Econ-5200-Project/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── Phase1_Data_Cleaning.ipynb
│   ├── Phase2_Replication.ipynb
│   └── Phase3_Extension.ipynb
├── .gitignore
└── README.md
