# README

Replication code for "Tracking Employment Changes in AI-Exposed Jobs."

The replication code builds off of Eloundou et al. (2024). Their original replication file is in code/gpts_are_gpts_script1.ipynb.

Code to map tasks to occupations is in `code/task_to_occupation.ipynb`. 

The main code to pull, clean, and analyze the data is in `code/cps_analysis.ipynb`. 

Run 
```
conda env create -f environment_reqs.yaml
```
to download the required packages. Activate the environment using 
```
conda activate research
```
