# comut-tRCC

This is an example to visualize the genotypic alterations or mutational landscape from 18 samples of pateints with a rare type of kidney cancer called translocation Renal Cell Carcinoma (tRCC). This visualize the no. of SNVs, INDELs and other alterations after variant calls and filtering from GATK mutect2 pipelines. All the data used in my analyses here are found in data files as csv format. 

Comut runs with the python packages- numpy, pandas, palettable adn matplotlib. Detail documnetaion on Comut and its usage are found here https://github.com/vanallenlab/comut

Background of the study - These are whole genome sequencing data from a cohort of tumor-normal pairs from patients with TFE3-TRCC to characterize at DFCI, This study is to test the hypothesis that there are specific mutations or alterations on the DNA that could be specific to TFE3-translocation RCC.

# File preps

Prepare all the categorical files with three columns as 'sample', 'category' and 'value'. Add mapping for all these file data to specify colors but make sure that color names are mixed with pallette nos from matplotlib. To add bar graph, prepare continuous data and add the mapping data similarly. The mapping arrangement should be done accordingly from bottom to top as we want to visualize. For example- if gender categorical data in the fig is at the top, keep the mapping data at the bottom.
