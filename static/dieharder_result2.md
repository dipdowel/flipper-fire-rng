Results of the [dieharder RNG tests](https://manpages.ubuntu.com/manpages/xenial/man1/dieharder.1.html) executed on file `/static/data2.txt`. 
Numbers in the file were collected using `ffr 150`.

```
$ dieharder -a -f data2.txt 
#=============================================================================#
#            dieharder version 3.31.1 Copyright 2003 Robert G. Brown          #
#=============================================================================#
   rng_name    |           filename             |rands/second|
        mt19937|                       data2.txt|  1.46e+08  |
#=============================================================================#
        test_name   |ntup| tsamples |psamples|  p-value |Assessment
#=============================================================================#
   diehard_birthdays|   0|       100|     100|0.50989209|  PASSED  
      diehard_operm5|   0|   1000000|     100|0.29304364|  PASSED  
  diehard_rank_32x32|   0|     40000|     100|0.68127126|  PASSED  
    diehard_rank_6x8|   0|    100000|     100|0.97841030|  PASSED  
   diehard_bitstream|   0|   2097152|     100|0.17866745|  PASSED  
        diehard_opso|   0|   2097152|     100|0.56763487|  PASSED  
        diehard_oqso|   0|   2097152|     100|0.13055552|  PASSED  
         diehard_dna|   0|   2097152|     100|0.86309317|  PASSED  
diehard_count_1s_str|   0|    256000|     100|0.49549982|  PASSED  
diehard_count_1s_byt|   0|    256000|     100|0.72464184|  PASSED  
 diehard_parking_lot|   0|     12000|     100|0.09561419|  PASSED  
    diehard_2dsphere|   2|      8000|     100|0.83056532|  PASSED  
    diehard_3dsphere|   3|      4000|     100|0.11000185|  PASSED  
     diehard_squeeze|   0|    100000|     100|0.67938228|  PASSED  
        diehard_sums|   0|       100|     100|0.44066977|  PASSED  
        diehard_runs|   0|    100000|     100|0.43926920|  PASSED  
        diehard_runs|   0|    100000|     100|0.84410004|  PASSED  
       diehard_craps|   0|    200000|     100|0.55455042|  PASSED  
       diehard_craps|   0|    200000|     100|0.77530894|  PASSED  
 marsaglia_tsang_gcd|   0|  10000000|     100|0.88285927|  PASSED  
 marsaglia_tsang_gcd|   0|  10000000|     100|0.32379056|  PASSED  
         sts_monobit|   1|    100000|     100|0.10687603|  PASSED  
            sts_runs|   2|    100000|     100|0.70534187|  PASSED  
          sts_serial|   1|    100000|     100|0.00791012|  PASSED  
          sts_serial|   2|    100000|     100|0.91801259|  PASSED  
          sts_serial|   3|    100000|     100|0.70221957|  PASSED  
          sts_serial|   3|    100000|     100|0.14314146|  PASSED  
          sts_serial|   4|    100000|     100|0.99942958|   WEAK   
          sts_serial|   4|    100000|     100|0.97499278|  PASSED  
          sts_serial|   5|    100000|     100|0.85287483|  PASSED  
          sts_serial|   5|    100000|     100|0.51044023|  PASSED  
          sts_serial|   6|    100000|     100|0.79033845|  PASSED  
          sts_serial|   6|    100000|     100|0.98881155|  PASSED  
          sts_serial|   7|    100000|     100|0.65831074|  PASSED  
          sts_serial|   7|    100000|     100|0.48093312|  PASSED  
          sts_serial|   8|    100000|     100|0.58693456|  PASSED  
          sts_serial|   8|    100000|     100|0.68506466|  PASSED  
          sts_serial|   9|    100000|     100|0.54201316|  PASSED  
          sts_serial|   9|    100000|     100|0.98640381|  PASSED  
          sts_serial|  10|    100000|     100|0.24473885|  PASSED  
          sts_serial|  10|    100000|     100|0.22342401|  PASSED  
          sts_serial|  11|    100000|     100|0.96450085|  PASSED  
          sts_serial|  11|    100000|     100|0.28539095|  PASSED  
          sts_serial|  12|    100000|     100|0.38902028|  PASSED  
          sts_serial|  12|    100000|     100|0.33038063|  PASSED  
          sts_serial|  13|    100000|     100|0.97409351|  PASSED  
          sts_serial|  13|    100000|     100|0.79224076|  PASSED  
          sts_serial|  14|    100000|     100|0.47654449|  PASSED  
          sts_serial|  14|    100000|     100|0.21122036|  PASSED  
          sts_serial|  15|    100000|     100|0.94508410|  PASSED  
          sts_serial|  15|    100000|     100|0.93000694|  PASSED  
          sts_serial|  16|    100000|     100|0.91991381|  PASSED  
          sts_serial|  16|    100000|     100|0.48153640|  PASSED  
         rgb_bitdist|   1|    100000|     100|0.45526378|  PASSED  
         rgb_bitdist|   2|    100000|     100|0.88973798|  PASSED  
         rgb_bitdist|   3|    100000|     100|0.66106183|  PASSED  
         rgb_bitdist|   4|    100000|     100|0.29988022|  PASSED  
         rgb_bitdist|   5|    100000|     100|0.85820750|  PASSED  
         rgb_bitdist|   6|    100000|     100|0.57062512|  PASSED  
         rgb_bitdist|   7|    100000|     100|0.92737828|  PASSED  
         rgb_bitdist|   8|    100000|     100|0.41924875|  PASSED  
         rgb_bitdist|   9|    100000|     100|0.79106737|  PASSED  
         rgb_bitdist|  10|    100000|     100|0.77960166|  PASSED  
         rgb_bitdist|  11|    100000|     100|0.78024300|  PASSED  
         rgb_bitdist|  12|    100000|     100|0.06850807|  PASSED  
rgb_minimum_distance|   2|     10000|    1000|0.50771910|  PASSED  
rgb_minimum_distance|   3|     10000|    1000|0.10795579|  PASSED  
rgb_minimum_distance|   4|     10000|    1000|0.05871834|  PASSED  
rgb_minimum_distance|   5|     10000|    1000|0.06711457|  PASSED  
    rgb_permutations|   2|    100000|     100|0.99542577|   WEAK   
    rgb_permutations|   3|    100000|     100|0.44292825|  PASSED  
    rgb_permutations|   4|    100000|     100|0.53808536|  PASSED  
    rgb_permutations|   5|    100000|     100|0.98740357|  PASSED  
      rgb_lagged_sum|   0|   1000000|     100|0.15071429|  PASSED  
      rgb_lagged_sum|   1|   1000000|     100|0.07535168|  PASSED  
      rgb_lagged_sum|   2|   1000000|     100|0.13573467|  PASSED  
      rgb_lagged_sum|   3|   1000000|     100|0.48082999|  PASSED  
      rgb_lagged_sum|   4|   1000000|     100|0.69303290|  PASSED  
      rgb_lagged_sum|   5|   1000000|     100|0.99333800|  PASSED  
      rgb_lagged_sum|   6|   1000000|     100|0.43804367|  PASSED  
      rgb_lagged_sum|   7|   1000000|     100|0.69087695|  PASSED  
      rgb_lagged_sum|   8|   1000000|     100|0.36050686|  PASSED  
      rgb_lagged_sum|   9|   1000000|     100|0.75691787|  PASSED  
      rgb_lagged_sum|  10|   1000000|     100|0.39639689|  PASSED  
      rgb_lagged_sum|  11|   1000000|     100|0.81046727|  PASSED  
      rgb_lagged_sum|  12|   1000000|     100|0.18630091|  PASSED  
      rgb_lagged_sum|  13|   1000000|     100|0.59078820|  PASSED  
      rgb_lagged_sum|  14|   1000000|     100|0.80429226|  PASSED  
      rgb_lagged_sum|  15|   1000000|     100|0.02898259|  PASSED  
      rgb_lagged_sum|  16|   1000000|     100|0.87047041|  PASSED  
      rgb_lagged_sum|  17|   1000000|     100|0.11126013|  PASSED  
      rgb_lagged_sum|  18|   1000000|     100|0.74683841|  PASSED  
      rgb_lagged_sum|  19|   1000000|     100|0.33971235|  PASSED  
      rgb_lagged_sum|  20|   1000000|     100|0.50312162|  PASSED  
      rgb_lagged_sum|  21|   1000000|     100|0.98634637|  PASSED  
      rgb_lagged_sum|  22|   1000000|     100|0.61993531|  PASSED  
      rgb_lagged_sum|  23|   1000000|     100|0.99416948|  PASSED  
      rgb_lagged_sum|  24|   1000000|     100|0.18896137|  PASSED  
      rgb_lagged_sum|  25|   1000000|     100|0.00936242|  PASSED  
      rgb_lagged_sum|  26|   1000000|     100|0.54417511|  PASSED  
      rgb_lagged_sum|  27|   1000000|     100|0.13283724|  PASSED  
      rgb_lagged_sum|  28|   1000000|     100|0.24294141|  PASSED  
      rgb_lagged_sum|  29|   1000000|     100|0.32740542|  PASSED  
      rgb_lagged_sum|  30|   1000000|     100|0.90876223|  PASSED  
      rgb_lagged_sum|  31|   1000000|     100|0.26725484|  PASSED  
      rgb_lagged_sum|  32|   1000000|     100|0.59182809|  PASSED  
     rgb_kstest_test|   0|     10000|    1000|0.42647648|  PASSED  
     dab_bytedistrib|   0|  51200000|       1|0.44128127|  PASSED  
             dab_dct| 256|     50000|       1|0.57367721|  PASSED  
Preparing to run test 207.  ntuple = 0
        dab_filltree|  32|  15000000|       1|0.17282825|  PASSED  
        dab_filltree|  32|  15000000|       1|0.67835008|  PASSED  
Preparing to run test 208.  ntuple = 0
       dab_filltree2|   0|   5000000|       1|0.11585087|  PASSED  
       dab_filltree2|   1|   5000000|       1|0.92806207|  PASSED  
Preparing to run test 209.  ntuple = 0
        dab_monobit2|  12|  65000000|       1|0.45629353|  PASSED  
leo@pigus4:~/flipper/repos/flipper-fire-rng$ 

```