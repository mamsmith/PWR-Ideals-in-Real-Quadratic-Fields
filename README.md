# PWR-Ideals-in-Real-Quadratic-Fields
This repository contains SageMath and PARI/GP code for computations/algorithms for PWR ideals in real quadratic fields.


## Algorithms
This directory contains the SageMath code for Algorithms 6.1, 6.2 and 6.3.

## Searching for PWR Ideals
This directory contains the PARI/GP code used to search for PWR ideals in real quadratic fields $\mathbb{Q}(\sqrt{d})$ with $d\equiv 3 \pmod 4$  and $d\equiv 1 \pmod 4$ and print the results to a text file. 
### d=1mod4
This codesearches exhaustively for PWR with $d \equiv 1 \pmod 4$, $d_1$ less than some assigned bound $b$, $d_2$ in the range $[d_1+1,2*d_1]$ and $k,l$ less than another assigned bound $c$. 

###d=3mod4
This codesearches exhaustively for PWR with $d \equiv 3 \pmod 4$, $d_1$ less than some assigned bound $b$, $d_2$ in the range $[d_1+1,2*d_1]$ and $k,l$ less than another assigned bound $c$. 
