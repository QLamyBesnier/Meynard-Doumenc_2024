# Data and code corresponding to the analysis of:

_Meynard-Doumenc et al. (2024) Oxidative stress constrains the evolution of phage host-range diversity in a microbial community_

There are two independant analysis:

- The analysis of the timeshift experiment.
- The analysis of the mutations present in the bacterial and phage clones.

### Data

The data necessary to reproduce the analysis can be found in the "Data" folder.

It is composed of a 4 files :

- *Timeshift_fermenter.csv*: a csv table containing the counts of each OTU in each sample. It is the only file required for the timeshift experiment analysis.
- *Bacteria_mutations_matrix.csv*: a csv table containing the list of mutations for each bacterial clone. Required for the analysis of the mutations.
- *Phage_mutations_matrix.csv*: a csv table containing the list of mutations for each phage clone. Required for the analysis of the mutations.
- *Interaction_matrix.csv*: a csv table containing which contains the infectivity each phage/bacteria couple (0 = no infection, 1 = infection). Required for the analysis of the mutations.

### Code

The code corresponding to the data analysis can be found in the "Code" folder.

It is composed of 2 RMarkdown files, one per analysis:

- *Timeshift_analysis.Rmd*: generates the figures found in the manuscript for the timeshift analysis (figures 3A and 3B).
- *Mutations.Rmd*: generates the results of mutations analysis (*Genomic mutations are associated to the evolution P10 host range* section in the manuscript).

### Issues

Feel free to report any code-related issue or question in the corresponding section of the GitHub repository or by emailing the corresponding authors of the manuscript.


