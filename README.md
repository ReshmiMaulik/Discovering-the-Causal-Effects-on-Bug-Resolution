# README: Causal Inference and Interpretability in Developer Interaction

The datasets utilized for this study include Eclipse, OpenStack, and Mozilla, which are stored in the files workingdataE.csv, workingdataO.csv, and Final_df_Mozilla.csv, respectively. The interaction network was constructed directly from the raw Mozilla dataset using the workflow implemented in Network_Creation.ipynb.

This notebook explores causal inference and interpretability techniques to understand the relationships between various factors in developer interactions, specifically focusing on how different variables impact 'ET' (estimated time).

The steps followed are:
1.  Setup and Data Loading
2.  Structural Causal Model (SCM)
3.  Causal Graph Learning with GES
4.  Model Interpretability with SHAP
5.  Causal SHAP Integration
6.  Refutation Tests
7.  Normalization and Global  Feature Importance


The version used are as follows:
causallearn version: 0.1.4.7
dowhy version: 0.0.0
numpy version: 2.0.2
pandas version: 2.2.2
networkx version: 3.6.1
matplotlib version: 3.10.0
seaborn version: 0.13.2
The random seed for NumPy is set to 0. 
