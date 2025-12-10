# The impact of read depth and read length on RNA-seq splicing analysis
****
This Github repository provides the code the for the publication Ladwig et al. 2026.

## Authors
- Annika Ladwig
- Melina Klostermann
- Kathi Zarnack

## 1 Preprocessing and alternative splicing analysis with MAJIQ
****
The Rmarkdown contains the code for the preprocessing of the raw reads and for the subsequent alternative splice analysis with MAJIQ.

The rendered HTML file is available at https://annikala.github.io/.

## 2 Impact of library characteristics on alternative splice analysis
****
The R scripts contain the code used to investigate the influence of read length (2.1a - *U2AF2* KD, 2.1b - *UPF1* KD) and read depth (2.2) on: 
- read alignment
- LSV detection
- LSV quantification
- alternative splicing event types distribution

## 3 Impact of library characteristics on the detection of local splice variations (LSVs) in lowly expressed genes
****

The R script '3_TPM_analysis.Rmd' contains the code for analysing the impact of read length and read depth on the detection of LSVs in lowly expressed genes. 

## 4 Metaanalysis of public RNA-seq datasets from ENCODE
****
The R script contains the code for the metaanalysis of public RNA-seq datasets from ENCODE to investigate the used read depth.

## 5 Metaanalysis of public RNA-seq datasets from SRA
****
The R script contains the code for the metaanalysis of public RNA-seq datasets from SRA to investigate the used read depth.

## 6 Simulation of quantifiable introns 
****
The R script contains the code for simulating the number of quantifiable introns depending on read length and read depth. 
Subsampling of an RNA-seq sample in HEK cells with originally 380 M reads and 150-nt read length is used to estimate the number of introns spanned by at least 10 reads, 
which we denote as quantifiable introns. 
