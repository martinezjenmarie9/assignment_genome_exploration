# Genome Assembly Inspection Report

# Species
Vulpes vulpes (red fox)

# NCBI Assembly Accession
GCF_048418805.1

# Objective
To inspect and interpret a genome assembly by examining assembly statistics, sequence length distribution, filtering effects, and potential protein-coding regions using ORF prediction.

# Tools Used
- Galaxy platform
- Fasta Statistics – to generate assembly statistics (total length, number of sequences, N50, L50, and GC content)
- Compute Sequence Length – to determine sequence/ORF lengths
- Sort tool – to arrange sequence lengths from largest to smallest and identify the longest sequences/ORF
- Filter sequences by length – to perform the ≥10 kb filtering experiment
- getorf (EMBOSS) – to identify potential open reading frames (ORFs)
- NCBI Assembly/Nucleotide database – source of the genome and selected scaffold sequence

# Important Settings
- Assembly statistics were generated using the complete genome FASTA.
- Filtering threshold: minimum sequence length of 10 kb.
- ORF prediction minimum size: approximately 300 bp.
- Standard genetic code was used for ORF prediction.

## Short Interpretation
The genome assembly showed relatively high continuity based on the large scaffold sizes, N50 value, and maximum sequence length. Short sequences contributed minimally to the total assembly size. ORF analysis identified potential protein-coding regions, but these require further validation before being considered real genes.
