## `analyses` directory for [RobertsLab/paper-crab](https://github.com/RobertsLab/paper-crab)      
---

### Directory contents

- Directory [BLAST-to-GOslim](https://github.com/RobertsLab/paper-crab/tree/master/analyses/BLAST-to-GOslim)      
contains files for getting the transcriptome `blast` output file annotated with GOslim terms. Associated Jupyter notebook: [notebooks/transcriptome-BLAST-to-GOslim.ipynb](https://github.com/RobertsLab/paper-crab/blob/master/notebooks/transcriptome-BLAST-to-GOslim.ipynb)

- [make-GOslim-pie.xlsx](https://github.com/RobertsLab/paper-crab/blob/master/analyses/make-GOslim-pie.xlsx)      
Excel file in which I created a pie chart for the count data for each GOslim term made. Made using this count data: [BLAST-to-GOslim/GOslim-P-pie.txt](https://github.com/RobertsLab/paper-crab/blob/master/analyses/BLAST-to-GOslim/GOslim-P-pie.txt), that was made in this jupyter notebook: [notebooks/transcriptome-BLAST-to-GOslim.ipynb](https://github.com/RobertsLab/paper-crab/blob/master/notebooks/transcriptome-BLAST-to-GOslim.ipynb)

- [stress-response-genes.tab](https://raw.githubusercontent.com/RobertsLab/paper-crab/master/analyses/stress-response-genes.tab)     
Made from this Rmd: [scripts/make-stress-response-list.Rmd](https://github.com/RobertsLab/paper-crab/blob/master/scripts/make-stress-response-list.Rmd). It's a list of all Trintiy IDs from the transcriptome associated with the GOslim term 'stress response'. 
