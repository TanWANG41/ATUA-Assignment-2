# ATUA-Assignment-2
GCN assignment for predicting PM2.5 across London Output Areas

## Contents
- `ATUA_Assignment_2.ipynb`: source notebook
- `ATUA_Assignment_2.html`: exported HTML version
## Data
The analysis uses the provided GeoJSON dataset of London Output Areas, including PM2.5 and urban attribute variables.

## Methods
The workflow includes:
1. exploratory data analysis
2. adjacency-based graph construction
3. GCN modelling in PyTorch Geometric
4. comparison with a linear regression baseline
5. evaluation using RMSE and R²

## Requirements
Main Python libraries used:
- geopandas
- pandas
- numpy
- matplotlib
- networkx
- scikit-learn
- torch
- torch-geometric
