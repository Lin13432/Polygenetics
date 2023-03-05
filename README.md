# Polygenetics

**Paper:** Worobey et al. (2014). A synchronized global sweep of the internal genes of modern 
avian influenza virus. Nature, April 2010, Vol. 508, No. 7495, p. 254-257

Worobey and colleagues investigate the evolutionary patterns of influenza A virus 
(IAV) in different hosts. In this work they first show that substantial variation in 
evolutionary rate between different clades can disturb the reconstruction of the 
evolutionary relationships. By using a molecular clock model that explicitly accounts 
for such among-clade rate variation, they recover more consistent patterns of 
evolution across all IAV genomic segments. 

**Data:** we will focus on the coding region of the PA segment. All alignments required for the 
analysis are provided. For the complete data set, a version with (PA_all.nex) and without 
(PA_all_wo_bat.nex) the bat outgroup is provided.

**Objective:** Perform maximum likelihood tree reconstruction for the sequence data. 
Investigate the temporal structure for each of the host-specific clades. Use BEAST to
separately estimate the IAV evolutionary rate in different host species, and reconstruct the 
evolutionary history under a clock model allowing different host lineages to evolve at 
different rates.
