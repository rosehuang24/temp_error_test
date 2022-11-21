## running command:

```
./run_lostruct.R \
        -t bp -s 1000 \
        -I SK_pop.txt \
        -i <temp_error_test> \
        -o <temp_error_test>
```


### error message:

```
Error in cmdscale(pc.distmat[!na.inds, !na.inds], k = opt$nmds) : 
  NA values not allowed in 'd'
Calls: cbind -> cmdscale
Execution halted
```


### the result html file if I used my customized script:
```     result/SK_chr27.summary.html ```
