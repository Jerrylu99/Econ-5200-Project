# ECON 5200 Data Project

This repository contains the replication project for ECON 5200.

The project replicates the Difference-in-Differences (DID) analysis from:

Card, D. and Krueger, A. (1994). Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania.

## Repository Structure

data/
- raw/ : original dataset
- processed/ : cleaned dataset

notebooks/
- 01_Data_Cleaning.ipynb : data cleaning and preparation
- 02_Replication_Analysis.ipynb : DID replication analysis

## Data

The dataset contains survey information from fast-food restaurants in New Jersey and Pennsylvania before and after the minimum wage increase.

## Method

The analysis applies a Difference-in-Differences (DID) framework comparing employment changes between New Jersey (treatment group) and Pennsylvania (control group).
