# Repository of Lee and Han (2023)

## Summary
Lee and Han (2023) underscores the importance of study design in single-cell differential gene expression (DGE) analysis.
We show that the true variance of DGE tests depends on the study design but the test may not accurately estimate the true variance.
As a result, both type 1 and 2 errors may increase.

## Folder description
1. [`nullpower`](https://github.com/hanbin973/DEGpaper/tree/main/nullpower) contains the codes used in the main simulation analysis.
The `.rds` files of the datasets used in the analysis can be obtained from
    - [Yazar et al.](https://cellxgene.cziscience.com/collections/dde06e0f-ab3b-46be-96a2-a8082383c4a1)
    - [Reichart et al.](https://cellxgene.cziscience.com/collections/e75342a8-0f3b-4ec5-8ee1-245a23e0f7cb)
    - [Reed et al.](https://cellxgene.cziscience.com/collections/48259aa8-f168-4bf5-b797-af8e88da6637)
2. [`perturb`](https://github.com/hanbin973/DEGpaper/tree/main/perturb) contains the codes for the perturbation dataset analysis.
The `.rds` files of the datasets used in the analysis can be obtained from
    - [Schmidt et al.](https://zenodo.org/records/5784651)
    - [Kang et al.](https://figshare.com/articles/dataset/PBMC_scRNAseq_Kang_2018_RDS_dgCMatrix/22572694)
The folder also contains two `.rds` files (`schdmit.result.rds` and `kang.result.rds`) storing the result of the analysis.

