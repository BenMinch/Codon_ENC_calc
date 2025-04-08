# Codon_ENC_calc
A wrapper for CodonW (a really old program) to make it run smoothly with modern genomic needs and with multiple files all at the same time. This will calculate ENC (effective number of codons) for a given genome or folder of genomes.

# Usage
This program utilizes codonW without the need to shorten gene names or run multiple times for multiple files.

`python calculate_enc.py -i input_folder -o output_folder`
* The input folder should be a directory of gene files (one per genome)
* The output folder can be any folder you want outputs to be saved to. All ENC files are saved in the output folder with the gene name as a column and the ENC value (from 20-61) as another.

## Codon usage
If you just want to know the codon usage patterns for a folder of genomes, the `codon_usage.py` script can do that. 

`python codon_usage.py -i input_folder -o output_file`
