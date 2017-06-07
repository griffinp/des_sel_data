# des_sel_data
Data from the Drosophila desiccation selection experiment described in Griffin et al. (2017) 'Genomic Trajectories to Desiccation Resistance: Convergence and Divergence among Replicate Selected Drosophila Lines' Genetics 205:871-890. DOI: 10.1534/genetics.116.187104

These files in 'sync' format (see https://sourceforge.net/p/popoolation2/wiki/Manual/ for format details) contain allele call count information for the mass-bred population (generation 0) and one of the resulting experimental lines after 13 generations of desiccation selection or control treatment. The five replicate desiccation selection lines are indicated as 'D1' to 'D5' and the five replicate control lines as 'C1' to 'C5'. (Note: selection was not performed every generation; see Methods section in the paper for details). 

The fifth column of the sync file contains the result of the Fisher exact test for allele frequency difference (see https://sourceforge.net/p/popoolation2/wiki/Manual/) in -log10(P-value) format.

The '*SNPS.txt' files contain chromosome and position information for either all SNPs detected in the mass bred vs generation-13 comparison indicated (e.g. C1_all_SNPs.txt.gz), or for the SNPs that were assessed as significantly differentiated between the mass bred and generation-13 pools (e.g. C1_sig_SNPs.txt.gz).

These files were used to produce Figure 1 of Griffin et al. (2017), with the script "manhattan_plots.R" (available at https://github.com/griffinp/desiccation-selection/blob/master/manhattan_plots.R). 
