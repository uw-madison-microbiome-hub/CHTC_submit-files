The purpose of this repsoitory is to consolidate numerous CHTC/HT condor submit files created by members of the microbiome community on UW-Madison campus to analyze their own microbiome data using High throughput computing. 

Follow this [link](https://uw-madison-microbiome-hub.github.io/CHTC_submit-files/CONTRIBUTING) to find a template on how to add submit files to this site.

## Submit files

#### [Run Many ANI comparisons on CHTC](https://github.com/sstevens2/ani_compare_dag)
This workflow runs many ANI comparisons, pairwise within sets of directories. It will run all pairwise comparisons for the fasta files that end in *.fna within each directory. You need to change the extensions to .fna if they are .fa or .fasta. These files should only be the nucleotide sequences for the coding regions. No tRNA or rRNA gene sequences should be included.  
Contact [Sarah Stevens](mailto:sarah.stevens@wisc.edu)

#### [Pipeline for running checkm on UW-Madison's CHTC or an HTCondor system](https://github.com/sstevens2/checkm-chtc-pipeline)
This pipeline includes scripts for running checkm on a group of genomes and getting back a group of files for each genome containing the completeness and redundancy results. This pipeline is written for an HTCondor system, specifically UW-Madison's CHTC's HPC cluster using this docker image for checkm.  
Contact [Sarah Stevens](mailto:sarah.stevens@wisc.edu)


