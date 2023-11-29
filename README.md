# Building-Energy-Efficiency-Data-Analysis
Project for UIUC Data Science Club Data Drive Competition

Research/Dataset Overview:
The rise of climate change has prompted global concerns about constructing efficient buildings, to minimze energy input and output. More precisely, over 50% of residential energy consumption is accounted for by energy spent in heating and cooling these structures. Thus, it is important to accurately determine the energy efficiency of a building in its planning phase before construction begins. In this project, we analyze UC Irvine’s dataset on residential housing structures and their corresponding energy input and output. 

The dataset consists of 768 samples of residential buildings. We are predicting two variables, the heating load (energy input) and cooling load (energy output). In addition, to make these preidction we will be relying on 8 features.

Features:
Relative Compactness
Surface Area - m²
Wall Area - m²
Roof Area - m²
Overall Height - m
Orientation - 2:North, 3:East, 4:South, 5:West
Glazing Area - 0%, 10%, 25%, 40% (of floor area)
Glazing Area Distribution (Variance) - 1:Uniform, 2:North, 3:East, 4:South, 5:West
Target Variables:
Heating Load - kWh 
Cooling Load - kWh

Questions we answer:
What is the best predictive model for determining the heating and cooling loads of residential buildings?
What aspects of residential structures (what feature) has the greatest effect on the heating and cooling load?
What can be done to minimze heating/cooling load?

Files Overview: 
Building_data.xlsx stores the datatset in excel format
Analysis.ipynb is a jupyter notebook in Python that comprises the data analysis on Building_data.xlsx, including the machine learning model training and feature engineering. 





