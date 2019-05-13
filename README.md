# Systems genetics toolkit using the BXD multi-omics datasets to probe gene function
Contains the R script used in the Cell Systems paper to perform systems genetics analysis, e.g. PheWAS, ePheWAS, and mediation analysis. 

## Dependencies: 

Install `emma` from http://mouse.cs.ucla.edu/emma/. 

```sh
    wget http://mouse.cs.ucla.edu/emma/emma_1.1.2.tar.gz
    R CMD INSTALL emma_1.1.2.tar.gz
```

Install other dependent packages `plyr`, `qtl`, `mlmm`, `intermediate`
```R
    install.packages("devtools")
    install.packages("plyr")
    install.packages("qtl")
    
    library(devtools)
    # install_github("Gregor-Mendel-Institute/mlmm")  # The MLMM library and repository have been renamed and moved to MultLocMixMod
    install_github("Gregor-Mendel-Institute/MultLocMixMod")
    install_github("simecek/intermediate")

```
### Reference: 
Li H, Wang X, Rukina D, Huang Q, Lin T, Sorrentino V, Zhang H, Arends D, McDaid A, Luan P, Ziari N, Velázquez-Villegas LA, Gariani K, Kutalik Z, Schoonjans K, Radcliffe RA, Prins P, Morgenthaler S, Williams RW, Auwerx J, An integrated systems genetics and omics toolkit to probe gene function. Cell Systems (2018) 6, 90-102. DOI: http://dx.doi.org/10.1016/j.cels.2017.10.016 
