# orcaNB2023_RSG
Code used to analyze genomics of redox sensor green sorted cells sampled from Orca Basin in 2023. Supporting Paris et al., in prep.

Code files and their functions:
orca_RSG_processing.rmd: going from raw reads to assembled contigs, including QC and annotation.

orca_RSG_genome_processing_public.rmd: from from assembled contigs to binned genomes, including QC, taxonomic ID, annotation, and mapping

orca_RSG_bin_cat_potential_public.rmd: assessing the metabolic potential of MAGs generated in orca_RSG_genome_processing_public.rmd using KEGG pathways in DRAM_v6.csv file, plotting

orca_RSG_rpS3_public.rmd: running GraftM to assess presence of unbinned ribosomal S3 proteins in active sorts, plotting. Produces rpS3vsMAGs.pdf file.

all other files are either input (metadata.csv) to organize sample names, or generated from the above code files.


