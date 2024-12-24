# CPM_EEG_Craving

This repository provides all the scripts and code required to perform **Connectome-Based Predictive Modeling (CPM)** analysis. CPM is a powerful method for predicting individual behavior using brain connectivity data.

## Background

Details about the CPM method can be found in the original publication:  
[Shen et al., Nature Protocols (2016)](https://www.nature.com/articles/nprot.2016.178.pdf) and related papers.  

The methodology and this repository are inspired and adapted from work by:  
1. **Xilin Shen**  
   - *Using connectome-based predictive modeling to predict individual behavior from brain connectivity*  
   - Nature Protocols, 12(3), 506-518, 2017.  
   - Citation: Shen X., Finn E.S., Scheinost D., Rosenberg M.D., Chun M.M., Papademetris X., Constable R.T.

2. **Yumeng Ju**  
   - GitHub repository: [https://github.com/jym115](https://github.com/jym115)

## Repository Contents

This repository includes:
- Scripts for preprocessing input data.
- Code for CPM analysis.
- Helper functions for performance evaluation and visualization.

## Preparation

### Input Data Requirements
To use the CPM method, you need two main datasets:

1. **Predictor Matrix (MxN):**  
   - `M`: Number of features (e.g., brain connectivity metrics).  
   - `N`
