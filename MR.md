MR and disease progression: challenges + opportunities
------------------------------------------------------

- Impossible to distinguish between confounding/reverse causation between exposure + outcome
- Use SNPs as instrumental variables to guard against confounding + reverse causation

- MR studies use '2-sample' method
    - Index SNPs are used as IVs for exposure
    - Same SNPs are then queried in the outcome
    - Compute slope between effects estimated in both exposure + outcome

- Assumptions
    - IV is associated with exposure
    - IV is independent of confounders
    - IV is independent of outcome when conditioned on exposure
    - IV is homogeneous on outcome | monotonicity of IV effect on exposure | no interaction between IV and exposure on outcome

- Interpretation
    - Lifetime exposure effect?
    - Context/critical-dependent exposure effect?
    - Genetic liability wrt exposure (T2D -> CAD?)
        - Consistent with notion of liability to RISK of outcome

- Heterogeneity (elephant in the room)
    - Horizontoal pleiotropy => heterogeneity of effect sizes
    - MR-Egger | Median-Estimator | Q-statistic?
    - READ! Bowden et al ''Improving the visualisation, interpretation and analysis of two-sampled summary data ...'' Int J Epi 2018

- Impact of collider bias in MR
    - IV _not_ associated with incidence path? (same as InSIDE assumption)
    - Inverse probability weighting? to get estimate of causal/mediating effect

MR in drug discovery and development
------------------------------------

- Around half of drug development programs will fail
- 2.6bn dollars on average per trial
- 2.6bn => ~20 space missions! :D
- GWAS results may improve success rate for trials
    - HMGCR identified in LDL GWAS, statin targets

- Example: GLP1R to recapitulate efficacy for GLP1R-agonists?
    - SNP was protective for T2D and CHD
    - Trial outcome was positive!

- Use UKBB for rapid investigation / test hypotheses
- MR to instrument genes/transcripts/proteins
- LoF screen in UKBB identifies 1ks of gene-phenotype links!
    - 8.5k pLOF variants
    - PheWAS with 2.3k traits
    - Assoc at 5% FDR
- PrediXcan TWAS in UKBB using GTEx
