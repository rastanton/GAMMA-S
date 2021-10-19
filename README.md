# GAMMA-S

Sequence matching tool

Requires: Python/3+, Biopython, and blat

Usage: > python3 GAMMA-S.py my_scaffolds.fasta gene_db.fasta My_output (options)

Optional arguments: 
  
  -a (--all): Includes all sequence matches, even overlaps
  
  -e (--extended): Writes out all mutations (default is to only list the number of mutations if > 10)
  
  -i (--percent_identity): The % match identity used by blat for gene alignments, default is 90
