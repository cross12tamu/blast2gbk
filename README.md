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

I) Fetch FASTA file based on desired protein for BLASTp

II) Run BLASTp with fetched FASTA file

III) Parse BLASTp Results

IV) IDentify "best" method from GBK file retrieval

    a) esearch
  
    b) elink
  
    c) efetch
  
V) FASTA export (if desired)

## Jupyter Notebook:
* Mostly the same as the `retrieveGBK.py` script; but contains more notes and description than the script.
