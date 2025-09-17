# Dynamic-LCA-Wastewater-Sludge-to-Nitrogen-Fertilizer
The objective of this study is to conduct a cradle-to-grave, dynamic and prospective lifecycle assessment of environmental tradeoffs due to the production of nitrogen fertilizer from unused wastewater treated sludge (i.e., biosolids) with direct concentrated solar thermal energy as the drying treatment process relative to ammonia production from natural gas and electricity via the conventional Haber Bosch process. Through DOE CRADA program, NREL partnered with industry professionals Solar Dynamics (and American Infrastructure Holdings) to discuss the parameters modelled and associated values considered for the lifecycle assessment of the proposed nitrogen fertilizer production system by leveraging primary data and engineering methods. 

Two publications; CRADA Report and STOTEN Journal

Two accompanying versions of python code, developed in Jupyter Notebook through Anaconda
# Environment setup
Python packages: 

pip install numpy

pip install pandas 

pip install os

pip install matplotlib

pip install math

pip install copy
# Required input files
Interpolated LiAISON lifecycke emissions factors

Input variable quantities for sensitivity analysis
# Brief description of code setup
The first cell of the Notebook defines the independent variables, and the second cell defines the dependent variables. Table 1 lists all independent and dependent variables modelled to parametrize the lifecycle foreground system of the proposed product pathway, including the linkage between different variables. The third cell of the Notebook calls the dependent variables with the correct independent variables specified in the input calls and brings together the outputs of different dependent variables. The fourth cell executes the logic of the first three cells to generate the annual quantities of lifecycle foreground material and energy flows which are derived by amortizing evenly across thirty years the estimated lifetime flow quantities and dividing by thirty years of annual nitrogen supplied (i.e., 5,320,000 kg N). As a final step, the fifth cell time-discretizes the logic of the first four cells by preserving the year of occurrence of the foreground flows modelled to produce annual foreground inventories unique for each year from 2020 to 2050. The time-discrete foreground inventories represent the quantities of flows that occur in each year rather than a single static foreground inventory of annual averages over total count of years and nitrogen delivered in the system lifetime.   
# Access to results
Comparison with study
