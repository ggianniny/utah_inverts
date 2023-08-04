## README - Utah Invert Data Project
#### Gordon Gianniny
#### Updated 07/25/2023

Data and code repository for Utah Aquatic Insect Decline project. Project objectives are to clean up long-term monitoring data from sites across Utah and test for trends in taxonomic richness, etc. over time. 

**Key Files:**

  * UTinvert_data_cleaning.Rmd - performs all data cleaning operations - inputs are raw data file .csv's (stored in raw_data folder), outputs are cleaned data file .csv's (stored in cleaned_data folder). 
  
  * UTinvert_data_cleaning_V2.Rmd - Is a simplified version of UTinvert_data_cleaning.Rmd. It carries out all of the same filtering and data manipulation tasks as the original file, but in a streamlined version with fewer exploratory figures. inputs are raw data file .csv's (stored in raw_data folder), outputs are cleaned data file .csv's (stored in cleaned_data folder)
  
  * UTinvert_exploration.Rmd - performs in-depth data exploration and initial analyses - inputs are cleaned data .csv's (stored in cleaned_data folder), output plots are stored in the "plots" folder. **NOTE** as of 7/25/23, this file runs off of the outputs of UTinvert_data_cleaningV2.Rmd. If you want to change any of the data cleaning steps before running this script, make the changes in V2 of the data cleaning script, NOT the original version. 
  

**Organization:**


  * All cleaned datasets are stored in the *cleaned_data* folder. The *FileInfo.MD* document in that folder has a brief description of each file. 
  
  * All figures produced by both scripts are stored in the *plots* folder. Figures showing the distribution, density trends, and elevational distribution of SGCNs from Utah and adjacent states are in the *sgcn_plots* folder. 
  


