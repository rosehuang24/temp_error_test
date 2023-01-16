## running command:

```
./run_lostruct.R \
        -t bp -s 10 \
        -I pop.txt \
        -i NW_023496964.1 \
        -o NW_023496964.1
```


### error message:

```
During startup - Warning message:
Setting LC_CTYPE failed, using "C" 
Finding PCs for chromsome NW_023496964.1 in file NW_023496964.1/contig_NW_023496964.1.recode.vcf.gz and writing out to NW_023496964.1/NW_023496964.1.pca.csv and NW_023496964.1/NW_023496964.1.regions.csv 
Warning messages:
1: In any(chrom.wins) : coercing argument of type 'double' to logical
2: In vcf_windower_snp(file = file, sites = sites, size = size, samples = samples) :
  Trimming from chromosome ends: NW_023496964.1: 1 SNPs.
Done finding PCs, computing distances.
   user  system elapsed 
  1.572   0.045   1.725 
Done computing distances, running MDS and writing results to NW_023496964.1/mds_coords.csv 
Error in cmdscale(pc.distmat[!na.inds, !na.inds], k = opt$nmds) : 
  NA values not allowed in 'd'
Calls: cbind -> cmdscale
Execution halted

```

