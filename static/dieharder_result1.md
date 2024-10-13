Results of the [dieharder RNG tests](https://manpages.ubuntu.com/manpages/xenial/man1/dieharder.1.html) executed on file `/static/data1.txt`. 
Numbers in the file were collected using `ffr 150`.

```
$ dieharder -a -f data1.txt 
#=============================================================================#
#            dieharder version 3.31.1 Copyright 2003 Robert G. Brown          #
#=============================================================================#
   rng_name    |           filename             |rands/second|
        mt19937|                       data1.txt|  1.44e+08  |
#=============================================================================#
        test_name   |ntup| tsamples |psamples|  p-value |Assessment
#=============================================================================#
   diehard_birthdays|   0|       100|     100|0.70794342|  PASSED  
      diehard_operm5|   0|   1000000|     100|0.52042537|  PASSED  
  diehard_rank_32x32|   0|     40000|     100|0.13299782|  PASSED  
    diehard_rank_6x8|   0|    100000|     100|0.70500280|  PASSED  
   diehard_bitstream|   0|   2097152|     100|0.98469009|  PASSED  
        diehard_opso|   0|   2097152|     100|0.53018152|  PASSED  
        diehard_oqso|   0|   2097152|     100|0.15591712|  PASSED  
         diehard_dna|   0|   2097152|     100|0.20431806|  PASSED  
diehard_count_1s_str|   0|    256000|     100|0.53217905|  PASSED  
diehard_count_1s_byt|   0|    256000|     100|0.32383538|  PASSED  
 diehard_parking_lot|   0|     12000|     100|0.77743129|  PASSED  
    diehard_2dsphere|   2|      8000|     100|0.02073532|  PASSED  
    diehard_3dsphere|   3|      4000|     100|0.91461983|  PASSED  
     diehard_squeeze|   0|    100000|     100|0.94628914|  PASSED  
        diehard_sums|   0|       100|     100|0.04006959|  PASSED  
        diehard_runs|   0|    100000|     100|0.81903439|  PASSED  
        diehard_runs|   0|    100000|     100|0.77578337|  PASSED  
       diehard_craps|   0|    200000|     100|0.92115680|  PASSED  
       diehard_craps|   0|    200000|     100|0.04410053|  PASSED  
 marsaglia_tsang_gcd|   0|  10000000|     100|0.81601935|  PASSED  
 marsaglia_tsang_gcd|   0|  10000000|     100|0.96584730|  PASSED  
         sts_monobit|   1|    100000|     100|0.06817590|  PASSED  
            sts_runs|   2|    100000|     100|0.85617310|  PASSED  
          sts_serial|   1|    100000|     100|0.05423940|  PASSED  
          sts_serial|   2|    100000|     100|0.13699479|  PASSED  
          sts_serial|   3|    100000|     100|0.33492162|  PASSED  
          sts_serial|   3|    100000|     100|0.07449320|  PASSED  
          sts_serial|   4|    100000|     100|0.69389345|  PASSED  
          sts_serial|   4|    100000|     100|0.84416820|  PASSED  
          sts_serial|   5|    100000|     100|0.58695552|  PASSED  
          sts_serial|   5|    100000|     100|0.85269196|  PASSED  
          sts_serial|   6|    100000|     100|0.50924820|  PASSED  
          sts_serial|   6|    100000|     100|0.69487556|  PASSED  
          sts_serial|   7|    100000|     100|0.97065009|  PASSED  
          sts_serial|   7|    100000|     100|0.44381554|  PASSED  
          sts_serial|   8|    100000|     100|0.90549622|  PASSED  
          sts_serial|   8|    100000|     100|0.60712774|  PASSED  
          sts_serial|   9|    100000|     100|0.15624816|  PASSED  
          sts_serial|   9|    100000|     100|0.27509938|  PASSED  
          sts_serial|  10|    100000|     100|0.03148110|  PASSED  
          sts_serial|  10|    100000|     100|0.31581349|  PASSED  
          sts_serial|  11|    100000|     100|0.06422404|  PASSED  
          sts_serial|  11|    100000|     100|0.91911266|  PASSED  
          sts_serial|  12|    100000|     100|0.30396536|  PASSED  
          sts_serial|  12|    100000|     100|0.46291706|  PASSED  
          sts_serial|  13|    100000|     100|0.38808477|  PASSED  
          sts_serial|  13|    100000|     100|0.97060890|  PASSED  
          sts_serial|  14|    100000|     100|0.05174236|  PASSED  
          sts_serial|  14|    100000|     100|0.95944602|  PASSED  
          sts_serial|  15|    100000|     100|0.04206965|  PASSED  
          sts_serial|  15|    100000|     100|0.18186252|  PASSED  
          sts_serial|  16|    100000|     100|0.30007148|  PASSED  
          sts_serial|  16|    100000|     100|0.93680381|  PASSED  
         rgb_bitdist|   1|    100000|     100|0.69490757|  PASSED  
         rgb_bitdist|   2|    100000|     100|0.58685113|  PASSED  
         rgb_bitdist|   3|    100000|     100|0.03463246|  PASSED  
         rgb_bitdist|   4|    100000|     100|0.87572917|  PASSED  
         rgb_bitdist|   5|    100000|     100|0.13140340|  PASSED  
         rgb_bitdist|   6|    100000|     100|0.69535088|  PASSED  
         rgb_bitdist|   7|    100000|     100|0.47703644|  PASSED  
         rgb_bitdist|   8|    100000|     100|0.32308512|  PASSED  
         rgb_bitdist|   9|    100000|     100|0.55413617|  PASSED  
         rgb_bitdist|  10|    100000|     100|0.97467270|  PASSED  
         rgb_bitdist|  11|    100000|     100|0.57203483|  PASSED  
         rgb_bitdist|  12|    100000|     100|0.57045023|  PASSED  
rgb_minimum_distance|   2|     10000|    1000|0.46719838|  PASSED  
rgb_minimum_distance|   3|     10000|    1000|0.98838420|  PASSED  
rgb_minimum_distance|   4|     10000|    1000|0.17141184|  PASSED  
rgb_minimum_distance|   5|     10000|    1000|0.00761542|  PASSED  
    rgb_permutations|   2|    100000|     100|0.50669481|  PASSED  
    rgb_permutations|   3|    100000|     100|0.65946158|  PASSED  
    rgb_permutations|   4|    100000|     100|0.53159985|  PASSED  
    rgb_permutations|   5|    100000|     100|0.89367372|  PASSED  
      rgb_lagged_sum|   0|   1000000|     100|0.38571460|  PASSED  
      rgb_lagged_sum|   1|   1000000|     100|0.06132447|  PASSED  
      rgb_lagged_sum|   2|   1000000|     100|0.95066762|  PASSED  
      rgb_lagged_sum|   3|   1000000|     100|0.26653334|  PASSED  
      rgb_lagged_sum|   4|   1000000|     100|0.68117615|  PASSED  
      rgb_lagged_sum|   5|   1000000|     100|0.75537258|  PASSED  
      rgb_lagged_sum|   6|   1000000|     100|0.96009129|  PASSED  
      rgb_lagged_sum|   7|   1000000|     100|0.34733688|  PASSED  
      rgb_lagged_sum|   8|   1000000|     100|0.11999834|  PASSED  
      rgb_lagged_sum|   9|   1000000|     100|0.48381452|  PASSED  
      rgb_lagged_sum|  10|   1000000|     100|0.24999552|  PASSED  
      rgb_lagged_sum|  11|   1000000|     100|0.40090332|  PASSED  
      rgb_lagged_sum|  12|   1000000|     100|0.19086033|  PASSED  
      rgb_lagged_sum|  13|   1000000|     100|0.81719264|  PASSED  
      rgb_lagged_sum|  14|   1000000|     100|0.82885570|  PASSED  
      rgb_lagged_sum|  15|   1000000|     100|0.80573722|  PASSED  
      rgb_lagged_sum|  16|   1000000|     100|0.50577932|  PASSED  
      rgb_lagged_sum|  17|   1000000|     100|0.14468277|  PASSED  
      rgb_lagged_sum|  18|   1000000|     100|0.16482099|  PASSED  
      rgb_lagged_sum|  19|   1000000|     100|0.66309568|  PASSED  
      rgb_lagged_sum|  20|   1000000|     100|0.51794831|  PASSED  
      rgb_lagged_sum|  21|   1000000|     100|0.68155547|  PASSED  
      rgb_lagged_sum|  22|   1000000|     100|0.22952143|  PASSED  
      rgb_lagged_sum|  23|   1000000|     100|0.55014075|  PASSED  
      rgb_lagged_sum|  24|   1000000|     100|0.91528815|  PASSED  
      rgb_lagged_sum|  25|   1000000|     100|0.96354497|  PASSED  
      rgb_lagged_sum|  26|   1000000|     100|0.54707494|  PASSED  
      rgb_lagged_sum|  27|   1000000|     100|0.79904395|  PASSED  
      rgb_lagged_sum|  28|   1000000|     100|0.98781829|  PASSED  
      rgb_lagged_sum|  29|   1000000|     100|0.54077514|  PASSED  
      rgb_lagged_sum|  30|   1000000|     100|0.93443457|  PASSED  
      rgb_lagged_sum|  31|   1000000|     100|0.24813480|  PASSED  
      rgb_lagged_sum|  32|   1000000|     100|0.11861708|  PASSED  
     rgb_kstest_test|   0|     10000|    1000|0.14633659|  PASSED  
     dab_bytedistrib|   0|  51200000|       1|0.98867472|  PASSED  
             dab_dct| 256|     50000|       1|0.70823914|  PASSED  
Preparing to run test 207.  ntuple = 0
        dab_filltree|  32|  15000000|       1|0.88262474|  PASSED  
        dab_filltree|  32|  15000000|       1|0.03664592|  PASSED  
Preparing to run test 208.  ntuple = 0
       dab_filltree2|   0|   5000000|       1|0.02351214|  PASSED  
       dab_filltree2|   1|   5000000|       1|0.63651764|  PASSED  
Preparing to run test 209.  ntuple = 0
        dab_monobit2|  12|  65000000|       1|0.35279394|  PASSED  
```