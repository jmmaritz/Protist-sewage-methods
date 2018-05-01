# Protist-sewage-methods
Methods for detecting protists in raw sewage

### DESCRIPTION

This fileset contains QIIME commands and outputs used to carry out the analysis in the manuscript:

Maritz, *et al*.  (2017) [An 18S rRNA Workflow for characterizing protists in sewage, with a focus on zoonotic Trichomonads][Paper] *Microb Ecol* 74: 923.

Raw sewage samples from a private apartment building in New York City were subjected to environmental marker gene sequencing for the 18S rRNA gene (targeting eukaryotes).


### DATA:

You will need to download the raw Illumina sequence data from the SRA under BioProject [PRJNA315104][Bioproject].

You will also need to download the curated database used in this analysis.
Information on this can be found in my Github repository [Curated-SILVA-Database][github_database] and the the complete database can be downloaded from [Figshare][Database]

Alternatively, I have provided QIIME formatted OTU files from the original analysis for download.


### REQUIREMENTS:

Trimmomatic 0.32, Qiime 1.8.0, ea_utils 1.1.2, python 2, USEARCH 8.0.1, blast 2.2.22
R, packages: "ggplot2", "extrafont"

[Paper]: https://doi.org/10.1007/s00248-017-0996-9 
[Bioproject]: https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA315104
[github_database]: https://github.com/jmmaritz/Curated-SILVA-Database
[Database]: https://doi.org/10.6084/m9.figshare.3114850.v1
