### crAssphage-kit: identify crAss-like phage in assembled metagenome viral contigs.
<br>

### 1. Introduce 

Prodigal-gv (https://github.com/apcamargo/prodigal-gv) was used to predict ORFs, hmmscan with an E-value threshold of 0.001 was used to align predicted ORFs against 15 HMM profiles from tree crAss-like phages marker genes.

```
(1). terminase large subunit:	TerL
(2). portal protein:	portal
(3). major capsid protein:	MCP
```

### 2. Usage

```
crAssphage-kit -l 10000  DB63.fasta.gz  DB63
``` 

### 3. Reference

```text
Yutin N, Benler S, Shmakov SA, et al. Analysis of metagenome-assembled viral genomes from the human gut reveals diverse putative CrAss-like phages with unique genomic features. Nat Commun. 2021;12(1):1044. Published 2021 Feb 16. doi:10.1038/s41467-021-21350-w

Gulyaeva A, Garmaeva S, Ruigrok RAAA, et al. Discovery, diversity, and functional associations of crAss-like phages in human gut metagenomes from four Dutch cohorts. Cell Rep. 2022;38(2):110204. doi:10.1016/j.celrep.2021.110204

``` 