Tissue-specific influence of gene expression on neurological and psych traits
-----------------------------------------------------------------------------
- GWAS SNPs are in non-coding regions
- Goal is to map SNPs to 'causal' genes
- 2-sample MR to estimate causal effect between GeneExpr + Outcome
- Extended MR to use multiple exposures (gene expression) with outcome
    - Single SNP MR using Wald Ratio
    - Performed colocalization analysis to post QC MR results
    
Interrogating horizontal pleiotropy
--------------------
- Horizontal pleiotropy (HP) is when a SNP instrument affects multiple exposures
- biases/confounds MR analysis
- MR-TRYX
    - Use outliers to identify novel factors? that influence outcome
- Outlier detection
    - SNPs identified using Cochran's Q statistic
