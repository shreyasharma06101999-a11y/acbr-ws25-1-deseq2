# create conda environment with miniconda
i am creating a conda environment for DESeq2 data analysis with R and bioconductor in my windows system using windows subsystem linux (wsl)

## code in WSL terminal
- start the wsl in windows
- type the following to create conda environment for r4.5 names as R4.5WS
```{cmd}
conda create --name R4.5WS
```

- Activate the R4.5WS conda environment as follows
```{cmd}
conda activate R4.5WS
```
- Install R4.5 in the R4.5WS conda environment
```{cmd}
conda install conda-forge::r-base
```
`conda-forge` is the channel from anaconda.org. [conda-forge for rbase r4.5] (https://anaconda.org/conda-forge/r-base)