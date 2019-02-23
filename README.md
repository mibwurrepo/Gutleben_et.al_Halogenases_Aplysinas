# Gutleben_et.al_Halogenases_Aplysinas (UNDER REVIEW)
A study investigating halogenase diversity and  microbial diversity in marine sponges of the genus Aplysina.

In this repository are all the files and codes used for reproducible data analysis.

Below is a short descriptions of the files

**Complete workflow** 

Halogenase_Diversity_Final_1.Rmd -R Markdown file containing all details and analysis scripts used in this study. This includes R code as well as bash commands, used for data processing on a Linux server. This document contains step-wise information on all other data files.


**Microbiome data** 

16S_ps.RDS                        -Phyloseq object containing 16S rRNA gene amplicon sequencing data, classified to Genus level (SILVA SSU 128 database) 


**Halogenase database**  

halo_db1_uniprot.fasta            -Halogenase database fasta file, manually curated, containing 5427 “halogenase” protein entries from the UniProt/SwissProt database

halo_db1_uniprot.tab              -Halogenase database file with protein descriptions


**Halogenase data files**

rep_seqs_cluster95.fasta          -Representative cluster sequences of halogenases, clustered at 95% sequence identity using uclust


**BLAST results**

halodb_rep_seqs_cl95.txt          -BLASTP Hit table (best 10 hits) of halogenase cluster sequences against Halogenase database

interpro_rep_seqs_cluster95.tsv   -InterProScan protein domain detection results


**Halogenase summarized results** 

halo_hits_annot_abundance.csv     -Abundance table of halogenase cluster sequences, amino acid sequence, closest match and description from the halogenase database


**Phylogenetic tree**  

tree_db.fasta                     -FASTA file with all sequences (including reference sequences and outgroups) used for building the phylogenetic tree
RAxML_bipartitions.halo_tree_db_raxml -Best-scoring ML tree with support values, 100 bootstraps



All questions or comments concerning this analysis can be directed at johanna.gutleben@wur.nl

