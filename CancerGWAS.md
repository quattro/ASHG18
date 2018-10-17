PanCancer detects novel risk variants in UKBB
---------------------------------------------
- Shared genetic risk among cancer types is unclear
- Investigate multiple cancer phenotypes
- Analyze GWAS results in UKBB
-- 300k controls / 400-13k cases
-- Common SNPs (MAF > 0.01)

- LDSC
-- 8? pairs of traits significant shared component of genetic risk
-- Several pairs of traits had negative genetic correlation
-- P-values all ~ 0.05 (corrected for # of tests?)

- ''Pleiotropic regions'' in GWAS
-- LD clump => investigate overlap

- Meta-Analysis (ASSET)
-- 374 independent index SNPs across 18 cancers (P < 1e-6; why not 1e-8?)
-- 23 SNPs had evidence of shared effects (P < 0.05 / 374)
--- Why not perform meta analysis using chi2 estimates? Should improve power due to diff signs?
-- 164 had evidence of shared _direction_ of effects (P < 0.05 / 374)

