# Dynamic-LCA-Wastewater-Sludge-to-Nitrogen-Fertilizer
Objective of study 

Two publications; CRADA Report and STOTEN Journal

Two accompanying versions of python code, developed in Jupyter Notebook through Anaconda
# Environment setup
Python packages 

install numpy

install pandas 

install os

install matplotlib

install math

install copy
# Required input files
Interpolated LiAISON lifecycke emissions factors

Input variable quantities for sensitivity analysis
# Brief description of code setup
The first cell of the Notebook defines the independent variables, and the second cell defines the dependent variables. Table 1 lists all independent and dependent variables modelled to parametrize the lifecycle foreground system of the proposed product pathway, including the linkage between different variables. The third cell of the Notebook calls the dependent variables with the correct independent variables specified in the input calls and brings together the outputs of different dependent variables. The fourth cell executes the logic of the first three cells to generate the annual quantities of lifecycle foreground material and energy flows which are derived by amortizing evenly across thirty years the estimated lifetime flow quantities and dividing by thirty years of annual nitrogen supplied (i.e., 5,320,000 kg N). As a final step, the fifth cell time-discretizes the logic of the first four cells by preserving the year of occurrence of the foreground flows modelled to produce annual foreground inventories unique for each year from 2020 to 2050. The time-discrete foreground inventories represent the quantities of flows that occur in each year rather than a single static foreground inventory of annual averages over total count of years and nitrogen delivered in the system lifetime.   
# Access to results
Comparison with study
