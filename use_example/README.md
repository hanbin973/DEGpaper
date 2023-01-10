# Repository of Lee and Han (2023)

## Summary
Lee and Han (2023) propose robust GLMs studied by Huber (1967), White (1982) and McCullagh (1983) as a powerful and robust method for performing differentially expressed gene (DEG) analysis on single-cell RNA sequencing (scRNA-seq) data. 
This page contains notebooks with use examples for libraries in `python` and `R` supporting the described method.

## Examples currently provided

1. `statsmodels.ipynb` (`python`)
2. `fixest.ipynb` (`R`)
3. `sandwich.ipynb` (`R`)

For `glmGamPoi`, checkout the [official documentation](https://bioconductor.org/packages/release/bioc/html/glmGamPoi.html).

In general, the former two libraries are faster than the last one which is based on `glm` command of `R base`.
Unlike the last one, the former two libraries fit GLMs through highly optimized `C/C++` under the hood. 
