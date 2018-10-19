Alkes Price
===========

LD-dependent architecture
-------------------------
- What does LD-dependent architecure mean?
    - Causal effect is dependent on LD _after_ conditioning on MAF
- S-LDSC
    - LLD: level of LD stratified by MAF quantile normalization
- LD-related annotations have strong relationship with selection
    - If SNP is older, has had more time to ''generate'' LD
- LD is itself correlated with some baseline annotations
    - Evidenced by decrease in enrichment in LD+MAF-stratified vs LD+MAF+baseline-stratified
- Joint effects of LD-related annotations is nearly exact match with forward simulation results
- LDSC vs LDAK performance difference is washed out when jumping to 4.6M HRC SNPs

Functional architectures
------------------------
- Low-frequency variant enrichment vs common-variant enrichment depends on selection
    - For non-synonymous ratio is ~ 5x
- Brain-related annotations boost power for rare variant analysis due to selection?
- Negative selection does not allow large effect sizes -> _flatten_ effect sizes 

Selection
---------
- Effective number of associated SNPs (`M_a`)
- Caution against using effective number of causal SNPs (`M_s`) due to power bias
- Stratified 4th moment LDSC
- Brain-related traits are particularly polygenic
- Common variants are more polygenic than low-frequency variants
- Polygenicity enrichment was proportional to heritability enrichment across functional categories
- Conserved variants are 15x enriched for polygenicity 
- GWAS effect sizes are _largely_ determined by negative selection
- Rare-variant architectures are _less_ dependent on negative selection

Takeaway
--------
LD-dependent architectures are CRITICAL for sensitive and accurate anaylses
