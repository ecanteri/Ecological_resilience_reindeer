# Reindeer_Appendix02
This repository contains the example code to run process-explicit models for reindeer.

Files and folders include:
- Reindeer_Appendix02.Rproj
- SimulationsWorkflow.Rmd
- ice_inv_prj.RDS
- reindeer_region_prj.RDS
- rt_humans_mean_prj.RDS
- rt_humans_sd_prj.RDS
- Data
- HS_PRJ
- GreenlandPolygon

SimulationsWorkflow.Rmd is a RMarkdown file containing a detailed explanation of the code used to run the process-explicit models, starting from importing and processing the data, creating the different generators that will define the processes simulated in the models and finally running the models. Part of the data gets generated following the .Rmd file, while other data is provided in the "Data" folder. This folder contains human density and standard deviation files (rt_humans_mean_prj.RDS, rt_humans_sd_prj.RDS), a land-time depended glacial ice mask (ice_inv_prj.RDS) and the study region for the reindeer (reindeer_region_prj.RDS). Five habitat suitability projections are also provided in the "HS_PRJ" folder. Finally, the "GreenlandPolygon" folder contains a shpefile of the region in Greenland where initial abundances are turned to 0 in the model, to avoid occupancy in the region at the beginning of the simulations. This code will produce and run 10 models.
