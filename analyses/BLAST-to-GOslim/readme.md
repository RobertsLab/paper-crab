## `analyses` from taking transcriptome `blast` output to GOslim in []()
--- 
 
Jupyter noteboook to get `blast` to GOslim --> [notebooks/transcriptome-BLAST-to-GOslim.ipynb](https://github.com/RobertsLab/paper-crab/blob/master/notebooks/transcriptome-BLAST-to-GOslim.ipynb)

### Directory contents: 

- [20200507.C_bairdi.Trinity.blastx.outfmt6](https://raw.githubusercontent.com/RobertsLab/paper-crab/master/analyses/BLAST-to-GOslim/20200507.C_bairdi.Trinity.blastx.outfmt6)    
`blast` output in format 6. Entire transcriptome against swissprot/uniprot database. Details here: [Post](https://robertslab.github.io/sams-notebook/2020/05/08/Transcriptome-Annotation-C.bairdi-Transcriptome-v2.0-Using-DIAMOND-BLASTx-on-Mox.html) 

- [Blastquery-GOslim.tab](https://raw.githubusercontent.com/RobertsLab/paper-crab/master/analyses/BLAST-to-GOslim/Blastquery-GOslim.tab)      
transcriptome `blast` results with GOslim terms

- [GOslim-P-pie.txt](https://raw.githubusercontent.com/RobertsLab/paper-crab/master/analyses/BLAST-to-GOslim/GOslim-P-pie.txt)      
counts of Trinity_IDs from trancriptome `blast` that fall under each GOslim term. Used to create a pie chart of proportions of genes that contribute to each GOslim. 

- [_blast-sep.tab](https://raw.githubusercontent.com/RobertsLab/paper-crab/master/analyses/BLAST-to-GOslim/_blast-sep.tab)       
file created in the jupyter notebook. It's the transcriptome `blast` output, but tab-delimited. Used in [scripts/make-stress-response-list.Rmd](https://raw.githubusercontent.com/RobertsLab/paper-crab/master/scripts/make-stress-response-list.Rmd) to create a list of genes that contribute to the GOslim term 'stress response' ([analyses/stress-response-genes.tab](https://raw.githubusercontent.com/RobertsLab/paper-crab/master/analyses/stress-response-genes.tab)). 

