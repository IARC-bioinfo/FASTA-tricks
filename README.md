# Tip and tricks for FASTA files

## Usefull tools

## Tip and tricks

### Create a bed file from a faidx index
For example with 1Mb regions:
```bash
bedtools makewindows -g reference.fasta.fai -w 1000000
```
