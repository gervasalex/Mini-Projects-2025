# Genomic Comparison of *Microsporidia MB* -Infected and Uninfected *Anopheles arabiensis*

## Abstract
The spread of *Microsporidia MB*, a symbiotic microbe in *Anopheles arabiensis*, offers a promising complementary strategy to traditional malaria control methods. This project aims to compare the genomes of *An. arabiensis* mosquitoes infected 
with *Microsporidia MB* (MB⁺) to those uninfected (MB⁻), with a focus on identifying copy number variations (CNVs) and other genetic differences, particularly in genes associated with insecticide resistance. 
Whole-genome sequencing (WGS) data from both groups will be analyzed using the *An. arabiensis Dongola* reference genome. Standard bioinformatics pipelines will be applied to assess sequence quality, align reads, and detect variants. 
Variant calling and annotation will be performed using tools such as BWA, SAMtools, BCFtools, and SnpEff/VEP, while structural variation will be investigated with CNVnator and DELLY. This analysis will enhance our understanding of host genetic responses to *Microsporidia MB*
and evaluate the genomic impact of infection in relation to insecticide resistance.

## Objectives

1. To assess sequence quality and align WGS data from MB⁺ and MB⁻ An. arabiensis mosquitoes to a reference genome.

2. To identify and annotate single nucleotide polymorphisms (SNPs), insertions, and deletions (indels) between infected and uninfected groups.

3. To detect and compare copy number variations and structural variants with a focus on insecticide resistance-associated genes.

4. To evaluate the potential functional impact of genetic variations linked to Microsporidia MB infection and their implications for vector control strategies.


## Data analysis pipeline

###   Quality check

```
fastqc /Kenya_microsporidia_sequence/ *_R1_001.fastq.gz /Kenya_microsporidia_sequence/ *_R2_001.fastq.gz --output output_fastqc/
```






