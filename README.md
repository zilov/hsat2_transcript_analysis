# HSAT2 transcript analysis

* [Human T2T-CHM13v2.0 genome](https://www.ncbi.nlm.nih.gov/assembly/GCF_009914755.1) was used to identify transcript localization. 
* Mapping of the transcript sequence on the genome was performed using the standalone version of [BLAST v2.12.0+](https://doi.org/10.1186/1471-2105-10-421) with parameters -task blastn and -perc-ident 0.8.
* The resulting mapping results were converted to BED format using [blast2bed](https://github.com/nterhoeven/blast2bed).
* [USCS Genome Browser](http://www.genome.org/cgi/doi/10.1101/gr.229102) of Human genome T2T-CHM13v2.0 (GCA_009914755.4) was used to visualize the localization of the transcript sequence on chromosomes.
