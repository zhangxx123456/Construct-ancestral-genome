# Construct-ancestral-genome

Construct the ancestral genome from the given population(s).

https://github.com/zhangxx123456/Construct-ancestral-genome




# Ussage:

python3    construct_ancestral_genome.py    Outputfile    Proportion_cutoff_of_haplotypes    Recombination_distance    Inputfiles



# Parameters:

Outputfile: The output file for recording results.

Proportion_cutoff_of_haplotypes: The lowest proportion of inferred ancestral haplotypes in all of the input files.

Recombination_distance:  If the selected haplotype was extended to the given length, it will occur a recombination event.

Inputfiles: One file or multiple files are allowed. All of the input files must have the completely consistent bi-allelic variants. '0' means the reference allele was selected to construct ancestral genomes. '1' means the alternative allele was selected to construct ancestral genomes. '.' means the no allele was selected to construct ancestral genomes.



# For example:

python3 construct_ancestral_genome.py   abc.chr1.txt.gz   0.2   6000   Test.dataset/A.chr1.txt.gz   Test.dataset/B.chr1.txt.gz   Test.dataset/C.chr1.txt.gz


