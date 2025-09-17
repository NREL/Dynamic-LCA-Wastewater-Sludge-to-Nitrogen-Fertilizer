# Dynamic-LCA-Wastewater-Sludge-to-Nitrogen-Fertilizer
The objective of this study is to conduct a cradle-to-grave, dynamic and prospective lifecycle assessment of environmental tradeoffs due to the production of nitrogen fertilizer from unused wastewater treated sludge (i.e., biosolids) with direct concentrated solar thermal energy as the drying treatment process relative to ammonia production from natural gas and electricity via the conventional Haber Bosch process. The temporal boundary is 31 years from from 2020 through 2050 and the spatial boundary is a typical biosolids processeing facility of 23,000 wet annual tons (functional unit) located in New Mexico. Through Department of Energy (DOE) Cooperative Research and Development Agreement (CRADA) program initiative, the National Renewable Energy Laboratory (NREL) partnered with industry professionals Solar Dynamics (and American Infrastructure Holdings) to discuss the parameters modelled and associated values considered for the lifecycle assessment of the proposed nitrogen fertilizer production system by leveraging primary data and engineering methods. Wastewater sludge to value products and lifecycle assessment exists in the literature, and this study is the first to produce a completely reproducible and publically available python-code based framework that is user adjustable for the parametrized lifecycle of the novel pathway of diverting wastewater sludge to nitogen fertilizer production via direct concentrated solar thermal energy.  

The primary outcomes of this study are two hand-written scientific publications, CRADA Techincal Report (DOI incoming) and STOTEN Journal Article (DOI incoming), and one pyhton-code based software publication (i.e., this Github repository). Due to the difference in scope of analysis reported by the CRADA Report and STOTEN Article, two accompanying versions of python code, developed in Jupyter Notebook through Anaconda, are both housed under this GitHub repository for the associated scientific publication. 
# Environment setup
install Anaconda

open Anaconda Powershell Prompt 

Type in the following commands line by line to 1) create a new python environment from scratch to dedicate to this GitHub repository and 2) install the python packages to the newly created environment that are required to run the python-coded scripts of this GitHub repository: 

conda create --name N_fert_lca_env

conda activate N_fert_lca_env

pip install numpy

pip install pandas 

pip install os

pip install matplotlib

pip install math

pip install copy
# Required input files
Interpolated LiAISON lifecycke emissions factors (liaison_results_lifecycle_EFs_interpolated_annual.csv)

Input variable quantities for sensitivity analysis (independent_variable_sensitivity.csv)
# Brief description of code setup
The first cell of the Notebook defines the independent variables, and the second cell defines the dependent variables. Table 1 lists all independent and dependent variables modelled to parametrize the lifecycle foreground system of the proposed product pathway, including the linkage between different variables. The third cell of the Notebook calls the dependent variables with the correct independent variables specified in the input calls and brings together the outputs of different dependent variables. The fourth cell executes the logic of the first three cells to generate the annual quantities of lifecycle foreground material and energy flows which are derived by amortizing evenly across thirty years the estimated lifetime flow quantities and dividing by thirty years of annual nitrogen supplied (i.e., 5,320,000 kg N). As a final step, the fifth cell time-discretizes the logic of the first four cells by preserving the year of occurrence of the foreground flows modelled to produce annual foreground inventories unique for each year from 2020 to 2050. The time-discrete foreground inventories represent the quantities of flows that occur in each year rather than a single static foreground inventory of annual averages over total count of years and nitrogen delivered in the system lifetime.   
# Access to results
The python-coded script associated with the Crada Report () and STOTEN Article () are meant to support the methods and results presented by the associated scientific publication. 

The databases (including png files) needed to generate the figures presented in the Crada Report () and STOTEN Article () are made available. 

The databases needed to generate the in-text statistics presented in the Crada Report () and STOTEN Article () are made available. 
