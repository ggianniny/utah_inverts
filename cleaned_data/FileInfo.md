## Cleaned datafile info

This document provides background info on each of the cleaned datasets in the "cleaned_data" folder. 

### Dataset Info: 

  1. **sample_richness.csv** - this file has sample metadata along with a column for taxonomic richness, total abundance, and total density for **all unique sample ID's**. No corrections have been made to account for differences in sampling method, sampling habitat, or sampling agency. Only non-insect adults (plus coleoptera and himiptera adults), larvae, and pupae are included. Samples classified to all taxonomic levels are included. All samples with a lab split of < 0.055 have been removed. 
  
  2. **site_5day_richness.csv** - this file has sample metadata along with taxonomic richness, total abundance, and total density  for each site, with replicates (considered to be any samples collected within 5 days of each other) combined to calculate mean richness & abundance across these "replicates." No corrections have been made to account for differences in sampling method, sampling habitat, or sampling agency. Only non-insect adults (plus coleoptera and himiptera adults), larvae, and pupae are included. Samples classified to all taxonomic levels are included. All samples with a lab split of < 0.055 have been removed. 
  
  3. **site_year_richness.csv** - has sample metadata plus mean taxonomic richness, total abundance, and total density  for each year at each site. No corrections have been made to account for differences in sampling method, sampling habitat, or sampling agency. Only non-insect adults (plus coleoptera and himiptera adults), larvae, and pupae are included. Samples classified to all taxonomic levels are included. All samples with a lab split of < 0.055 have been removed. 
  
  4. **comid_year_richness.csv** - has sample metadata plus mean taxonomic richness, total abundance, and total density  for each year in each COMID segment. No corrections have been made to account for differences in sampling method, sampling habitat, or sampling agency. Only  non-insect adults (plus coleoptera and himiptera adults), larvae, and pupae are included. Samples classified to all taxonomic levels are included. All samples with a lab split of < 0.055 have been removed. 
  
  5. **longterm_site_richness.csv** - has all of the columns in *site_year_richness.csv*, but only for sites with four or more years of data. Also has a column for elevation, which was calculated using GeoNames API based off of the srtm3 elevation model. 
  
  6. **longterm_comid_richness.csv** has the same columns as *comid_year_richness.csv*, but only for COMIDs with four or more years of data. 
  
  7. **taxa_densities.csv** has sample metadata and taxonomic information for each taxa in each sample, along with abundance and density (sample abundance/sample area) for that taxa. No corrections have been made to account for differences in sampling method, sampling habitat, or sampling agency. Only non-insect adults (plus coleoptera and himiptera adults), larvae, and pupae are included. Samples classified to all taxonomic levels are included. All samples with a lab split of < 0.055 have been removed.
  
  