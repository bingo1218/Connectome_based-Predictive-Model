CPM_EEG_Craving
This repository provides all the scripts and code required to perform Connectome-Based Predictive Modeling (CPM) analysis. CPM is a powerful method for predicting individual behavior using brain connectivity data.

Background
Details about the CPM method can be found in the original publication:
Shen et al., Nature Protocols (2016) and related papers.

The methodology and this repository are inspired and adapted from work by:

Xilin Shen

Using connectome-based predictive modeling to predict individual behavior from brain connectivity
Nature Protocols, 12(3), 506-518, 2017.
Citation: Shen X., Finn E.S., Scheinost D., Rosenberg M.D., Chun M.M., Papademetris X., Constable R.T.
Yumeng Ju

GitHub repository: https://github.com/jym115
Repository Contents
This repository includes:

Scripts for preprocessing input data.
Code for CPM analysis.
Helper functions for performance evaluation and visualization.
Preparation
Input Data Requirements
To use the CPM method, you need two main datasets:

Predictor Matrix (MxN):

M: Number of features (e.g., brain connectivity metrics).
N: Number of subjects.
This matrix includes the features used as predictors across all subjects.
Outcome Vector (Mx1):

This vector contains the predicted outcome values (e.g., behavioral scores) for each subject.
In neuroscience applications, particularly using functional connectivity data, the Predictor Matrix may be in the format MxMxN, where:

M x M represents the connectivity between nodes, ROIs, or sensors.
N is the number of subjects.
Example Data Preparation
For EEG functional connectivity data:

Construct a 3D matrix MxMxN:
M x M = connectivity measures (e.g., correlation, coherence) between regions or electrodes.
N = number of participants.
Getting Started
Ensure your data matches the required format.
Follow the scripts provided in this repository to preprocess, train, and evaluate the CPM model.
Author and Acknowledgements
This script was created by Hangbin Zhang and is inspired by:

Xilin Shen (Shen et al., 2017)
Yumeng Ju (GitHub Repository)
Citation
If you use this repository, please cite:
Shen, X., Finn, E.S., Scheinost, D., Rosenberg, M.D., Chun, M.M., Papademetris, X., & Constable, R.T. (2017). Using connectome-based predictive modeling to predict individual behavior from brain connectivity. Nature Protocols, 12(3), 506.

