# 16S rRNA sequence extraction from Barrnap outputs

## Introduction
This is a simple automated Shell script that uses the Barrnap ribosomal RNA predictor (https://github.com/tseemann/barrnap) output gff files with 16S gene positions as input to extract single 16S rRNA sequence from original genome FASTA sequence files.

## Usage
```
% ./16S_sequence_Barrnap.sh GFF FASTA
```

* Where GFF is the outputs from Barrnap and FASTA is the original FASTA sequence.
* This script will generate the final sequence file named FASTA-16S.fna, this should contain only single 16S sequence predicted by Barrnap - only the first 16S rRNA sequence predicted will be extracted using this script.

## Dependencies

* samtools: http://www.htslib.org/
* bedtools: http://bedtools.readthedocs.io/en/latest/
