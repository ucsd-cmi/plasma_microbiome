# Microbial genes in plasma data to predict cancer
Bacterial genera can be used to predict cancer and distinguish cancer types. This attempts to see if gene calls can be used in the same way.  

Steps:  
- decontam.Rmd: remove contaminant genera due to cross-well contamination.  
- normalize.Rmd: Use voom and snm to normalize data.
- ML_plasma.Rmd: Run machine learning to predict cancer 
