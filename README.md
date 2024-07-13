# Pioneer-project

Download "All_data.zip" and decompress. This files contains all the data needed for reproducing results for my paper. There are 3 folders in the "All_data" folder that are named after GEO accessions, and each of them contains the following materials: RNA-seq data in ".xlsx" and ".txt" format, group information in ".csv" format, and R script for DGE analysis. Another folder named "barplot" contains one R scipt and all the data needed to produce all the barplots presented in my paper. 

The RNA-seq data for GSE261670 can't be uploaded directly onto this GitHub project because it is too large. Please download it from GEO by going to "supplementary files" in GEO accession GSE261670 and custom download the files for samples 119141 to 119149. After downloading the files, add all of them into one folder and name the folder "kallisto" so that the R code can correctly import the data. 

Run all the R scipts to reproduce results. You might want to change the code for the "set.wd" (setting working directory) functions since they are currently set to the settings of my laptop. 

Thanks! 

