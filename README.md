This repository contains three folders:

1. rules : This folder contains datalog programs used.

2. queries : This folder contains training and test queries log.
Each line in the log has the following format:
Query <space> features <space> QSQ-R time <space> MS time <space> 1/0
1 indicates that MS was faster
0 indicates that QSQ-R was faster.

3. Models : This folder contains pickled objects for SVM classifier 
for all datasets.

LUBM(1K), DBpedia and Claros datasets can be downloaded or
generated as described in the reference paper here https://www.academia.edu/15194149/WebPIE_a_web-scale_parallel_inference_engine
