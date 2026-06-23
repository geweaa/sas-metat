This repository contains the R script used to analyze the metatranscriptomes discussed in the manuscript 'Low prokaryotic growth efficiency enhances the carbon demand estimate for the Central Arctic Ocean' by Ashish Verma et al. 

The raw data (20 metatranscriptomes) were deposited at the [European Nucleotide Archive](https://www.ebi.ac.uk/ena) with PRJEB64858 as accession id. The following files are required in the R script ```sas-metat.qmd```. Files marked with an asterix have been deposited in [Figshare](https://doi.org/10.6084/m9.figshare.32112655).

* Metadata including accession id's and sequence library id's: ```sample_key.tsv```
* Read coverage (in tpm) of each ORF: ```user_assembly.prokka.counts.tsv.gz```*
* Functional annotation: ```user_assembly.prokka.kofamscan-uniq.tsv.gz```*
* Taxonomic annotation (with both NCBI and GTDB as references): ```gtdb_ncbi_merged.tsv.gz```*
* Gene list: ```genelist-merged.tsv.gz```

A comparison was done with the metatranscriptome data (```KO_metaT.norm.tsv.gz```) from [Salazar et al. (2019)](https://doi.org/10.1016/j.cell.2019.10.014) using non-metric dimensional scaling (NMDS) while including samples from the South Atlantic Ocean, North Atlantic Ocean, and Arctic Ocean. For this, the files ```tara-kos-metat.tsv.gz``` and ```tara-meta.tsv``` are required and these can be found in the metatdenovo subdirectory.

