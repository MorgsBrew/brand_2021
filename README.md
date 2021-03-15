This thesis has been written in Microsoft Word 2016 (Mac) while all the analysis and visualizations have been done in R. RStudio has been a critical component of this Thesis and is the core component of moving toward reproducible research. Unfortunately, the lack of a formalized workflow with dedicated channels for collaborative input leaves the reproducibility of this system in an unreproducible state. At the onset, a solid workflow for data capture, analysis, processing and collaboration should be outlined that will significantly improve the overall process of compiling a thesis. 
An attempt has been made to extract the working chunks of code that form part of this Thesis. The data required for the work in this thesis have been compiled into a repository with data objects saved with .Rdata and .rds extensions that can be shared to recreate the analysis and visualization on request. The code is organized into chapters that correspond to the three experimental chapters within this thesis. To include them as txt would create an unnecessarily long document. 
The code is organized in the following format:
o	chpt2.Rmd
o	chpt3.Rmd
o	chpt4.Rmd
o	setup.Rmd
o	/data
o	PhD_supplementary_information-r-code.Rproj
The code chunks in the .Rmd files call for the relevant data from the /data folder for the analysis and visualizations. In order to reproduce these analysis it will be necessary to open the “PHD_supplementary_information-r-code.Rproj” in RStudio, identify the code chucks required and run the necessary lines of code. This is my attempt to provide a foundation for recreating the results of my analysis and adding to the building of a more streamlined mechanism of reproducibility.
