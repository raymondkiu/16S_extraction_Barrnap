# 16S_sequence_Barrnap
Automated 16S sequence extraction using Barrnap output gff files

This is a simple automated Shell script that uses the Barrnap (https://github.com/tseemann/barrnap) output gff files with 16S gene positions to extract single 16S rRNA sequence from original genome FASTA sequence files.

Usage:

$ ./16S_sequence_Barrnap.sh GFF FASTA

Where GFF is the outputs from Barrnap and FASTA is the original FASTA sequence.
This script will generate the final sequence file named FASTA-16S.fna, this should contain only single 16S sequence predicted by Barrnap.
