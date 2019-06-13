# CH-Stone-HPCs
HPC data for original/modified CH-Stone benchmarks
This repository contains the HPC data for some of the CH_Stone benchmarks.

The **unmod-data/** directory contains the HPCs for the original CH_Stone programs, run on the RPis.


The **mod-data/** directory contains the same HPCs for the CH_Stone benchmarks but after slight modifications,
representative of some malicious activity. These modifications include change in the lengths of keys, number of bit shifts,
number of loops for encryption etc.

Inside both sub-directories, there are files for seperate programs, and then there is one file unmod/mod.csv
which contains the shuffled HPC data from all the programs. These two files have been used as +ve/-ve datasets respectively,
to train machine learning models to detect the minor changes made to the program(via malicious activity). 
