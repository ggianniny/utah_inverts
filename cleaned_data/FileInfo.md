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
  
  8. **high_zapada_info.csv** has site info (coordinates, elevations, stream names, etc.) for all sites over 3000m with *Zapada* observations. 
  
  9. **sgcns.csv** has taxonomic info, sample metadata, taxa density, site elevation, and listing states for SGCN taxa from Utah, Colorado, Arizona, Nevda, Idaho, and Wyoming that are present in the dataset. 
  
  10. **site_ecoregions.csv** has sample metadata and taxonomic data along with added columns for ecoregion name and ecoregion ID.
  
  11. **eco_richness_density.csv** has taxonomic richness and density calculations for each utah ecoregion and year combo. Samples with fewer than 300 observations have been dropped from the dataset, and samples with over 300 observations have been randomly subsampled to 300 individuals. In addition to overall richness and mean density, there are also columns for richness per site and mean density per site to account for variation in # sites sampled per year. 
  
  12. **subsetted_full.csv** has sample metadata and taxonomic info, ecoregion data, and elevation data. Samples with <300 individuals have been dropped, and the remaining samples have been randomly subsetted to 300 individuals. 
  
  13. **statewide_richness_density.csv** has taxonomic richness and density calculations for the entire state for each year in the record. Samples with fewer than 300 observations have been dropped from the dataset, and samples with over 300 observations have been randomly subsampled to 300 individuals. In addition to overall richness and mean density, there are also columns for richness per site and mean density per site to account for variation in # sites sampled per year. 
  
  