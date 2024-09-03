# Protracted neuronal recruitment in the temporal lobe of young children

### Overview
Code used in the analysis of the study ["Protracted neuronal recruitment in the temporal lobe of young children", Nascimento et al. 2024, Nature](https://www.nature.com/articles/s41586-023-06981-x). Data can be browsed and downloaded at [Cellxgene](https://urldefense.com/v3/__https:/cellxgene.cziscience.com/collections/cae8bad0-39e9-4771-85a7-822b0e06de9f__;!!LQC6Cpwp!q7GtI6Hr33GOrbUctey7B60hpl5e06880bMAhGkLvqrOoEFX52xWela-dlbsn8dkpO0wiS-yBfLqcdGNE7_DlhLfK_dInugn$). This repository contains all the code used to generate the final Seurat
objects and analyses. The code is organized in separate notebooks for each step of the analysis:

1.  [Merging all samples in a single dataset](1.merging/1.merging.rmd)

2.  [Label transfer to identify specific neuronal populations](2.label_transfer/2.label_transfer.qmd)

3.  [Monocle and lineage trajectory analyses](3.monocle/3.monocle.rmd)

4.  [Subpopulations of LAMP5+ neurons](4.lamp5/4.lamp5.Rmd)

5.  [WGCNA](5.wgcna/5.wgcna.rmd)

6.  [Figures](6.figures/6.figures.qmd)
