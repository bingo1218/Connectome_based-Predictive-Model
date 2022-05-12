# Connectome_based Predictive Model

The detail description of this method could be found in https://www.nature.com/articles/nprot.2016.178.pdf and other published papers.

This repository includes all the related scripts/code that you can use to conduct CPM analysis.

This script is created by Hangbin Zhang and adapted/inspired by:

Xilin Shen: [1] Shen X., Finn E.S., Scheinost D., Rosenberg M.D., Chun M.M., Papademetris X., Constable R.T. "Using connectome-based predictive modeling to predict individual behavior from brain connectivity.", Nature Protocols 12.3 (2017): 506.

Yumeng Ju:https://github.com/jym115

Preparation:

you need to have two matrices for to construct. The first one is a MxN matrix (here, M includes everything you want to use as predictors acrros N subject), the other one is a Mx1 matrix, which includes the outcome (predicted value) of each one among M subjects.

However, in neuroscience, or more specificantly, if you use functional connectivity data, the first matrix could be "MxMxN" format, where MxM means the connectivity between nodes/ROI/sensors x nodes/ROI/sensors. 

