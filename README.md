# Analysis of Quebec Delta SARS-CoV-2 from White-Tailed Deer

[![DOI](https://zenodo.org/badge/694358857.svg)](https://zenodo.org/badge/latestdoi/694358857)

This repo contains code used to generate the results and figures described in the "Characterizing Delta SARS-CoV-2 infection and host response in free-ranging white-tailed deer in southern Quebec, Canada" paper.

Not all data are included in this repo (size limits, licensing) and the intent is to document what analyses were performed rather than providing automatic reproduction of results and figures.

## `notebooks/`

This directory contains Bash, Python and R Jupyter Notebooks used for analyses performed on the reference mapped assemblies of the QC WTD SARS-CoV-2.

* R Jupyter Notebooks require the [IRkernel](https://irkernel.github.io/installation/)
* Bash Jupyter Notebooks require the [bash_kernel](https://pypi.org/project/bash_kernel/)

## `data/`

Contains data and output related to the analyses performed.

## `conda-envs/`

Contains YAML files describing Conda environments for analyses conducted in R and Python.

## Pre-print

Genomic and transcriptomic characterization of Delta SARS-CoV-2 infection in free-ranging white-tailed deer (Odocoileus virginianus).

Jonathon D. Kotwa, Briallen Lobb, Ariane Massé, Marianne Gagnier, Patryk Aftanas, Arinjay Banerjee, Andra Banete, Juliette Blais-Savoie, Jeff Bowman, Tore Buchanan, Hsien-Yao Chee, Peter Kruczkiewicz, Finlay Maguire, Allison J. McGeer, Kuganya Nirmalarajah, Catherine Soos, Lily Yip, L. Robbin Lindsay, Andrew C. Doxey, Oliver Lung, Bradley Pickering, Samira Mubareka.

bioRxiv 2022.01.20.476458; doi: https://doi.org/10.1101/2022.01.20.476458 

```bibtex
@article {Kotwa2022.01.20.476458,
	author = {Jonathon D. Kotwa and Briallen Lobb and Ariane Mass{\'e} and Marianne Gagnier and Patryk Aftanas and Arinjay Banerjee and Andra Banete and Juliette Blais-Savoie and Jeff Bowman and Tore Buchanan and Hsien-Yao Chee and Peter Kruczkiewicz and Finlay Maguire and Allison J. McGeer and Kuganya Nirmalarajah and Catherine Soos and Lily Yip and L. Robbin Lindsay and Andrew C. Doxey and Oliver Lung and Bradley Pickering and Samira Mubareka},
	title = {Genomic and transcriptomic characterization of Delta SARS-CoV-2 infection in free-ranging white-tailed deer (Odocoileus virginianus)},
	elocation-id = {2022.01.20.476458},
	year = {2023},
	doi = {10.1101/2022.01.20.476458},
	publisher = {Cold Spring Harbor Laboratory},
	abstract = {White-tailed deer are susceptible to SARS-CoV-2 and represent a highly important species for surveillance. Nasal swabs and retropharyngeal lymph nodes from white-tailed deer (n=258) collected in November 2021 from Qu{\'e}bec, Canada were analyzed for SARS-CoV-2 RNA. We employed viral genomics and transcriptomics to further characterize infection and investigate host response to infection. We detected Delta SARS-CoV-2 (AY.44) in deer from the Estrie region; sequences clustered with human sequences from GISAID collected in October 2021 from Vermont, USA, which borders this region. Mutations in the S-gene and a deletion in ORF8 encoding a truncated protein were detected. Host expression patterns in SARS-CoV-2 infected deer were associated with the innate immune response, including signalling pathways related to anti-viral, pro- and anti-inflammatory signalling, and host damage. Our findings provide preliminary insights of host response to SARS-CoV-2 infection in deer and underscores the importance of ongoing surveillance of key wildlife species for SARS-CoV-2.Competing Interest StatementThe authors have declared no competing interest.},
	URL = {https://www.biorxiv.org/content/early/2023/05/09/2022.01.20.476458},
	eprint = {https://www.biorxiv.org/content/early/2023/05/09/2022.01.20.476458.full.pdf},
	journal = {bioRxiv}
}
```
