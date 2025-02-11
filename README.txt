Project Title: Reservoirs of spoilage fungi in the built environment of cultured dairy facilities vary by season and location

Shuai Man (a), Sarah Daly(a), Xiaoxuan Shi(a), Jingzhang Feng(a), Abigail B. Snyder(a)
(a)Department of Food Science, Cornell University, Ithaca, NY


Contact information for Corresponding Authors 
*Abigail B. Snyder, Sarah E. Daly 
Department of Food Science, Cornell University, Ithaca, NY 14853, USA (abs276@cornell.edu, sed84@cornell.edu)  

############################################################################################################################
SOFTWARE INFORMATION 

.XLS, .XLSX .CSV (MICROSOFT EXCEL Microsoft® Excel® 2019 MSO (Version 2312 Build 16.0.17126.20132) 64-bit))
.DOCX (MICROSOFT WORD Microsoft® Word 2019 MSO (Version 2312 Build 16.0.17126.20132) 64-bit)
.RMD (RStudio Files, RStudio Version "Elsbeth Geranium" Release (7d165dcf, 2022-12-03) for Windows)
.qza (QIIME artifact, QIIME 2 Version 2022.2)
.PDF .TIF (IMAGE Files)
.TXT (TEXT FILE)

#####################################################################################################################
SEQUENCE INFORMATION

ITS sequences from this study are openly available at the BioProject accession number PRJNA1123599 at https://www.ncbi.nlm.nih.gov/sra/PRJNA1123599 .  


####################################################################################################################
Step 1. Sequences were uploaded in QIIME 2 See:  "QIIME 2 workflow-ITS Sequence Processing";
Step 2. Statistical Calculations & Visualizations were completed in RStudio using QIIME 2 artifacts, See remaining folders

####################################################################################################################

Figure 1 and Table S.5, S.3
R File:  Spoiled_product_pie_bar.rmd
Input:  
•	20240814_genera_database.csv 
•	Fac1_genera.csv
•	Fac2_genera.csv
•	Fac3_genera.csv


Figure2 Heatmaps, Permanova, Table S.10, Table S.9, Table S.11
Figure2Heatmaps.rmd
Inputs:  
•	otu-table-dn-99-SFWS-q20.qza
•	rooted_tree.qza
•	unite-dyn-11-22-ITS-taxonomy-otu.qza 
•	Metadata_ITS2.txt 
•	keep.csv


Alpha diversity and boxplots
alpha_div_boxplot.rmd
Inputs:  
•	otu-table-dn-99-SFWS-q20.qza
•	rooted_tree.qza
•	unite-dyn-11-22-ITS-taxonomy-otu.qza 
•	Metadata_ITS2.txt 
•	keep.csv

differential abundance analysis
diff_abundance_analysis.rmd
Inputs:  
•	otu-table-dn-99-SFWS-q20.qza
•	rooted_tree.qza
•	unite-dyn-11-22-ITS-taxonomy-otu.qza 
•	Metadata_ITS2.txt 
•	keep.csv

relative abundance of genera tables s.4, s.6, s.7, s.8
Inputs:  
Relative_Abundance_calc.rmd
•	otu-table-dn-99-SFWS-q20.qza
•	rooted_tree.qza
•	unite-dyn-11-22-ITS-taxonomy-otu.qza 
•	Metadata_ITS2.txt 
•	keep.csv
Network Analysis 
Inputs:  
Relative_Abundance_calc.rmd
•	otu-table-dn-99-SFWS-q20.qza
•	rooted_tree.qza
•	unite-dyn-11-22-ITS-taxonomy-otu.qza 
•	Metadata_ITS2.txt 
•	keep.csv


Venn diagram
Venn_diagram.Rmd
Input
•	Wall_Ceiling_Genera_RA.csv
•	Door_Genera_RA.csv
•	Fan_vent_genera_RA.csv
•	floor_genera_RA.csv


Side by side swabbing Data
Side_by_side_analysis.rmd

•	Metadata_pairs.txt
•	rooted_tree.qza
•	otu_table_dn_99-q20.qza
•	unite-dyn-11-22-ITS-taxonomy-otu-q20.qza

YM Boxplots 

YM_boxplot.rmd
Input:  
"BE_meta.csv"


Chi Square correlation 

20240730_Chi Square Correlation_sd,rmd
INput:
BE_meta.csv

Mini relative abundance 

Relative_Abun_per_object.rmd

Inputs:  
•	otu-table-dn-99-SFWS-q20.qza
•	rooted_tree.qza
•	unite-dyn-11-22-ITS-taxonomy-otu.qza 
•	Metadata_ITS2.txt 
•	keep.csv
