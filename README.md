# Differential-Expression-using-DESeq2

Differential expression analysis pipeline was ran on a RNA-seq dataset comparing treatment and control breast cancer cells with a goal to understand what genes play a role in suppressing NRDE2. mRNA profiles of 3 control cell lines and 3 NRDE2-treated (NRDE2 silenced with RNAi) cells fastq files were obtained for a total of 6 "samples".  The libraries are single-end (SE) sequenced on an Illumina NextSeq platform.

The pipeline follows preprocessing the raw data and then running Salmon to gather the transcript counts, using tximport to convert TPM to gene-level counts and conduct DGE with DESeq2. 


Reference: Jiao AL, Perales R, Umbreit NT, et al. Human nuclear RNAi-defective 2 (NRDE2) is an essential RNA splicing factor. RNA (New York, N.Y.). 2019 Mar;25(3):352-363. DOI: 10.1261/rna.069773.118. PMID: 30538148; PMCID: PMC6380277.
