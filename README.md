# Synaptotagmin-13 orchestrates pancreatic endocrine cell egression and islet morphogenesis

This repository contains scripts to reproduce the results of the single-cell data from:
M.Bakthi et al., "Synaptotagmin-13 orchestrates pancreatic endocrine cell egression and islet morphogenesis", _submitted_, 2022


The notebooks contain code for the following analyses:

**scRNA-seq of mouse pancreatic epithelial cells:**  
- _mouse_embryonic_BastidasPonce2019.ipynb_ --> Analysis of embryonic mouse pancreatic epithelial cells, data from Bastidas-Ponce, Tritschler et al., Development, 2019, doi:10.1242/dev.173849 (GEO: GSE132188)  

**scRNA-seq of human pancreatic epithelial cells:**    
- _curate_Cao2020.html_, _human_fetal_Cao2020.ipynb_ --> Curation and analysis of embryonic human pancreatic epithelial cells, data from Cao et al., Science, 2020, 10.1126/science.aba7721 (https://descartes.brotmanbaty.org/bbi/human-gene-expression-during-development/)  

- _human_invitro_Veres2019.ipynb_ --> Analysis of in vitro differentiated human pancreatic epithelial cells, data from Veres et al., Nature, 2019, https://doi.org/10.1038/s41586-019-1168-5 (GEO: GSE114412, GSE114412_Stage_5.all.processed_counts.tsv.gz)  


Note that the analysis was done with scanpy v1.4. Some functions have changed in newer versions of scanpy. For other package versions please consult the notebook. Numeric results can vary depending on package versions and e.g. affect clustering.

If the materials in this repo are of use to you, please consider citing the above publication as well as the primary data sources.

If you have any questions about the data or analysis feel free to contact us. :)