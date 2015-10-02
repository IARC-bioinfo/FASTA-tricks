# Tip and tricks for FASTA files
- [Usefull tools](https://github.com/IARC-bioinfo/FASTA-tricks#usefull-tools)
- [Tip and tricks](https://github.com/IARC-bioinfo/FASTA-tricks#tip-and-tricks)
 - [Create a bed file from faidx index](https://github.com/IARC-bioinfo/FASTA-tricks#create-a-bed-file-from-a-faidx-index) 

## Usefull tools

## Tip and tricks

### Create a bed file from a faidx index
For example with 1Mb regions:
```bash
bedtools makewindows -g reference.fasta.fai -w 1000000
```
