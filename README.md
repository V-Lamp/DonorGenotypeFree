# DonorGenotypeFree
R Script for donor geneotype free analysis of donor fraction for SOT recipients

[![DOI](https://zenodo.org/badge/267396914.svg)](https://zenodo.org/badge/latestdoi/267396914)


## Quick Start using provided example data

1. Save Results_Test.csv and panel_template_MOAT.csv to a folder

2. Save and open the genotypefree R script

3. Update the working directory to the folder with the Results_Test.csv and panel_template_MOAT.csv on line 21

4. Install the mixtools package

5. Run the script


This will create a run folder for each run where the Results_Test.csv is saved, with a folder for each sample in the run. 
An overview of the results is output as a .pdf with 4 plots of processing steps.
Summary statistics are also saved as well as intermediate processing steps.


The Results_Test.csv can be saved into any subfolders. 
The filename MUST begin with "Results" to be found with the script.
This is example data only. ID30 and ID31 are mock examples representing approximately 10% and 5% donor fraction.
Columns can be added or deleted, and number of counts changed to experiment with the data. However the normalmixEM may fail if there is no variance in the data, or it does not include enough of each of the expected reciepient/donor genotype combinations.


Please refer to the published paper for study info
