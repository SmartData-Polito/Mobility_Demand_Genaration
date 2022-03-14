# Mobility_Demand_Generation

This repository contains the python notebook and a portion of the dataset used for the paper 'Demand Model Generation from Traces: Adaptive KDE Data-Driven Optimization', submitted for the 25th IEEE International Conference on Intelligent Transportation Systems (IEEE ITSC 2022).

There are twopython notebooks:

-"Amsterdam_models.ipynb" contains the code to generate different demand models with the related Weekday 23 time-slot dataset, contained in this repository. It also generates the kde samples and saves them in .pickle format. Theese are necessary to generate the contour plot illustrated in the paper.

-"Amsterdam_plots.ipynb" contains the code to produce the most important contour plots (figures 2c, 8a, 8b, 8c) illustrated in the paper. For doing that, it is necessary to read the .pickle files containing the KDE's samples.

For both, it is sufficient to import the python notebook and the .csv file containing the dataset in a jupyter enviroment.

More instructions are contained inside each notebook.
