# HapSeq2
HapSeq2 is a program for genotyping calling and haplotype phasing from next generation sequencing data using haplotype information from jumping reads. Previously, we developed a Hidden Markov Model (HMM) based method for genotype calling and haplotype phasing from next generation data that can take into account jumping reads information across two adjacent potential polymorphic sites. Our method extends the HMM in the Thunder program (Li, et al., 2010) and explicitly models jumping reads information as emission probabilities conditional on the states of adjacent sites (Zhi et al., 2012). The method is implemented in the program, HapSeq. The program is written with C++ and based on the source code of Thunder program provided by Drs. Yun Li and Goncalo Abecasis. The detailed description of the method implemented in HapSeq can be found in our manuscript (Zhi et al., 2012).

Recently, we extended our methods to incorporate the haplotype information of multiple adjacent and/or non-adjacent sites from sequencing reads. Our model is inspired by the model implemented in HASH that was originally designed to phase individual genomes (Bansal et al., 2008). We develop a new hybrid MCMC algorithm that combines the Gibbs sampling algorithm of HapSeq and Metropolis-Hasting algorithm similar to that of HASH and is computationally feasible. We show by simulation and real data from the 1000 Genomes Project that our model offers superior performance for haplotype phasing as well as genotype calling for population NGS data over existing methods. The new method is implemented in the program, HapSeq2. For the detailed description of the method implemented in HapSeq2, please refer to our manuscripts (Zhi et al., 2012; Zhang and Zhi, 2013).

[HapSeq2 Progran Manual](https://github.com/ZhiGroup/HapSeq2/blob/master/HapSeq2-Manual.pdf)

[Wiki Page for HapSeq2](https://github.com/ZhiGroup/HapSeq2/wiki)

## Older version: HapSeq

HapSeq is a program for genotyping calling and haplotype phasing from next generation sequencing data using haplotype information from jumping reads. We developed a Hidden Markov Model (HMM)-based method for genotype calling and haplotype phasing from next generation data that can take into account jumping reads information across two adjacent potential polymorphic sites. Our method extends the HMM in the Thunder program (Li, et al., 2010) and explicitly models jumping reads information as emission probabilities conditional on the states of adjacent sites. The method is implemented in the program, HapSeq. The program is implemented with C++ and based on the source code of Thunder program provided by Drs. Yun Li and Goncalo Abecasis. For the detailed description of the method implemented in HapSeq, please refer to our manuscript (Zhi et al., 2012).


[HapSeq Manual](https://github.com/ZhiGroup/HapSeq2/blob/master/HapSeq-Manual.pdf)



