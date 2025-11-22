# start R
To start R statistical programming language type R in the command linne of the R4.5WS conda environment
```{cmd}
R
```
# install packages for bioconductor
installing `BiocManager` from CRAN (comprehensive R arcchival network) using `install.packages()` function in r base. please type the following,
```{R}
install.packages("BiocManager")
```
install `Biostrings` bioconductor package using `BiocManager::instal()` function.
```{R}
BiocManager::install("Biostrings")
```
