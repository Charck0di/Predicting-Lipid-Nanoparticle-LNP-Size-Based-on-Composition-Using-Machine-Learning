Predicting LNP Size via Machine Learning
Predicting LNP Size via Machine Learning
This project aims to predict the size of lipid nanoparticles (LNPs) based on their lipid composition using machine learning techniques. LNPs are critical in drug delivery systems, and understanding how their formulation influences size can accelerate formulation optimization and experimental design.

Overview
Input features:

Ionizable Lipid (%)

Helper Lipid (%)

PEG Lipid (%)

Phospholipid (%)

Target: LNP Size (nm)

Approach:

Data preprocessing and visualization

Feature correlation analysis

Supervised learning using Random Forest Regression

Model evaluation via residuals and prediction accuracy

Feature importance interpretation

Visualizations
The project includes:

Distribution plots for all lipid components

Correlation heatmap

Predicted vs. Actual LNP size plot

Residual error distribution

Feature importance bar chart

Pair plot of all features and target

Technologies Used
Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Jupyter Notebook

How to Use
Clone this repository.

Load the Jupyter Notebook.

Ensure your dataset includes the required columns:

'Ionizable_Lipid_%', 'Helper_Lipid_%', 'PEG_Lipid_%', 'Phospholipid_%', 'LNP_Size_nm'

Run all cells to train the model and generate visualizations.
