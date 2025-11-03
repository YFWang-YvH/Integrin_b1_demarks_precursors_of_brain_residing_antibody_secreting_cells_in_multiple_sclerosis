# **Project: Integrin b1 demarks precursors of brain-residing antibody-secreting cells in multiple sclerosis**

**Project background:**

B cells are deemed a driving force behind the onset of multiple sclerosis (MS). We earlier found that a subset of B cells, the CXCR3+ memory B cells, are triggered to migrate to central nervous system (CNS) compartments from MS patients (Van Langelaar et al., 2021). It is hypothesized that once migrated to the CNS, these cells locally mature into the long-living antibody secreting cells (ASCs) that we detected in the MS brain (Bogers et al., 2023). It remains unclear however, what drives the migration and maturation of CXCR3+ memory B cells in MS, and what features could contribute to the subsequent local residency of ASCs in the MS brain.

**Project aim:**

To in-depth characterize B cells that express CXCR3, ultimately to dissect features that could contribute to their pathogenic effector mechanism in MS. 
 
**Experimental design:**

For this project, we sorted total CD19+ B cells from thawed peripheral blood mononuclear cells (PBMCs) from healthy donors (n=3). Together with Dr. Eric Bindels from the department of Hematology at Erasmus MC, we performed 5' scRNAseq runs using the 10x Genomics platform using Next-GEM v2 reagents. For each run, we aimmed to load approximately 16k sorted CD19+ B cells. 

---

# **CXCR3_sc_HCpaper.Rmd**

This script analyses the three healthy donor samples from this scRNAseq dataset for the this paper. 

1. matrix data are loaded into a seurat object 
2. Raw data quality check and filtering
3. Data normalization and reduce dimensionality
4. Cell clustering and filtering 
5. Filter out naive B cells (out of research interest)
6. Differential expression analysis




