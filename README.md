## README - Utah Invert Data Project
#### Gordon Gianniny
#### Updated 05/18/2023

Data and code repository for Utah Aquatic Insect Decline project. Project objectives are to clean up long-term monitoring data from sites across Utah and test for trends in taxonomic richness, etc. over time. 

**Key Files:**

  * UTinvert_data_cleaning.Rmd - performs all data cleaning operations - inputs are raw data file .csv's (stored in raw_data folder), outputs are cleaned data file .csv's (stored in cleaned_data folder). 
  
  * UTinvert_exploration.Rmd - performs in-depth data exploration and initial analyses - inputs are cleaned data .csv's (stored in cleaned_data folder), output plots are stored in the "plots" folder. 
  
  * UTinvert_modeling.Rmd - performs modeling based on patterns observed in UTinvert_exploration.Rmd. Inputs are cleaned data .csv's (stored in cleaned_data folder), output plots are stored in the "plots" folder. 
  

**Organization:**


  * All cleaned datasets are stored in the *cleaned_data* folder. The *FileInfo.MD* document in that folder has a brief description of each file. 
  
  * All figures produced by both scripts are stored in the *plots* folder. Figures showing the distribution, density trends, and elevational distribution of SGCNs from Utah and adjacent states are in the *sgcn_plots* folder. 
  


