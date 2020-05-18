## `analyses` directory for [RobertsLab/paper-crab](https://github.com/RobertsLab/paper-crab)      
---

### Directory contents

- Directory [BLAST-to-GOslim](https://github.com/RobertsLab/paper-crab/tree/master/analyses/BLAST-to-GOslim)      
contains files for getting the transcriptome `blast` output file annotated with GOslim terms. Associated Jupyter notebook: [notebooks/transcriptome-BLAST-to-GOslim.ipynb](https://github.com/RobertsLab/paper-crab/blob/master/notebooks/transcriptome-BLAST-to-GOslim.ipynb)

- [DAVID-enrich-temp.txt](https://raw.githubusercontent.com/RobertsLab/paper-crab/master/analyses/DAVID-enrich-temp.txt)       
Output from DAVID of enriched GO terms. Background --> uniprot accession IDs from the [`blast` output from transcriptome version 1.5](https://raw.githubusercontent.com/RobertsLab/project-crab/master/analyses/BLAST_to_GOslim/_blast-sep.tab), Gene list --> uniprot accession IDs from the [DEG list comparing elevated and decreased temperature treatments](https://raw.githubusercontent.com/RobertsLab/paper-crab/master/analyses/DEG-temperature.tab).  

- [DEG-temperature.tab](https://raw.githubusercontent.com/RobertsLab/paper-crab/master/analyses/DEG-temperature.tab)     
List of 424 DEGs found in this Rmd ([scripts/02-DeSeq-Temperature.Rmd](https://github.com/RobertsLab/paper-crab/blob/master/scripts/02-DeSeq-Temperature.Rmd)), comparing libaries 8-11, combining infection status, based on elevated and decreased temperature treatments from day 2. 

- [DEG-temperature.txt](https://raw.githubusercontent.com/RobertsLab/paper-crab/master/analyses/DEG-temperature.txt)        
Saved DEG list with Trinity ID column named "Trinity_ID". Did that in excel. 

- [make-GOslim-pie.xlsx](https://github.com/RobertsLab/paper-crab/blob/master/analyses/make-GOslim-pie.xlsx)      
Excel file in which I created a pie chart for the count data for each GOslim term made. Made using this count data: [BLAST-to-GOslim/GOslim-P-pie.txt](https://github.com/RobertsLab/paper-crab/blob/master/analyses/BLAST-to-GOslim/GOslim-P-pie.txt), that was made in this jupyter notebook: [notebooks/transcriptome-BLAST-to-GOslim.ipynb](https://github.com/RobertsLab/paper-crab/blob/master/notebooks/transcriptome-BLAST-to-GOslim.ipynb)

- [stress-response-genes.tab](https://raw.githubusercontent.com/RobertsLab/paper-crab/master/analyses/stress-response-genes.tab)     
Made from this Rmd: [scripts/make-stress-response-list.Rmd](https://github.com/RobertsLab/paper-crab/blob/master/scripts/make-stress-response-list.Rmd). It's a list of all Trintiy IDs from the transcriptome associated with the GOslim term 'stress response'. 

- [transcriptome-blast-GO.tab](https://raw.githubusercontent.com/RobertsLab/paper-crab/master/analyses/transcriptome-blast-GO.tab)      
Annotate new transcriptome (version 2.0) `blast` ouptut with GO. Tables `join`-ed using this Rmd: [scripts/transcipt-blastout-with-GO.Rmd](https://github.com/RobertsLab/paper-crab/blob/master/scripts/transcipt-blastout-with-GO.Rmd). 

