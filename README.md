# BLASTp --> GBK record
## Summary:
Method(s) that from a BLASTp, and from the HSP protein accessions, retrieve the GBK record for each accession. Additionally, a FASTA file containing all HSPs can be output if desired.


## Requirements:
* BioPython Modules
    * Blast
    * Entrez
    * SeqIO

## Script:
Several Parts:

1) Fetch FASTA file based on desired protein for BLASTp

2) Run BLASTp with fetched FASTA file

3) Parse BLASTp Results

4) IDentify "best" method from GBK file retrieval

    a) esearch
  
    b) elink
  
    c) efetch
  
5) FASTA export (if desired)

## Jupyter Notebook:
* Mostly the same as the `retrieveGBK.py` script; but contains more notes and description than the script.
