# Soil_Listeria_ARG_manuscript
Code used to replicate data analyses in the manuscruipt Evidence of horizontal gene transfer and environmental selection impacting antibiotic resistance evolution in soil-dwelling _Listeria_.

## Required Python packages
- numpy 
- pandas 
- pyshp 
- seaborn 
- scikit-bio 
- statsmodel 
- basemap
- scipy
- statannotations
- colorcet
- geopy 
- matplotlib 
- mpu
- biopython
- haversine
- python-Levenshtein

**Note:**
For running the R code in the Jupyter notebook install rpy2 package using `pip install rpy2`

- Use the command '%load_ext rpy2.ipython' for using this library before executing the R code in the python notebook
- Now in order to run any cell having R code, ensure that %%R is at the top of the code. Similarly to run any line of R code, ensure that %R is in front of that line.

## Structure
```Soil_Listeria_ARG.ipynb```: code used for analysis and generate plots in Fig. 1, 4 and Supplementary Figs. 1, 2, 4, 6, 7.

This code include analysis for:

```Fig. 1a```: Compute the proportions of present and functional ARGs across _Listeria_ genomes.\
```Fig. 1b```: Compute the proportions of functional ARGs across _Listeria_ species.\
```Supplementary Fig. 1a```: Compute the proportions of present ARGs across _Listeria_ species.\
```Fig. 1c```: Compute the richness of present and functional ARGs across _Listeria_ species.\
```Fig. 1d```: Compute the Spearman correlation between genetic similarity to _L. monocytogenes_ and average richness of functional ARGs.\
```Supplementary Fig. 1b```: Compute the Spearman correlation between genetic similarity to _L. monocytogenes_ and average richness of present ARGs.\
```Fig. 1e```: Map functional ARGs richness among _Listeria_ genomes across the United States.\
```Supplementary Fig. 1c```: Map present ARGs richness among _Listeria_ genomes across the United States.

```Fig. 4a```: Compute Spearman's partial correlation between ARG richness in _Listeria_ genomes and environmental variables, controlled for genetic similarity for _L. monocytogenes_.\
```Fig. 4b```: Compute Variation partitioning analysis (VPA) for ARG richness, controlled for genetic similarity.\
```Fig. 4c```: Compute two-sided Mann-Whitney test for environmental variables among _Listeria sensu stricto_ and _sensu lato_ species and present it using a volcano plot.\
```Fig. 4f```: Compute Mantel tests between ARG sequence dissimilarity and environmental variables.\
```Fig. 4g```: Conduct VPA for _norB_ sequence diversification.\
```Supplementary Fig. 4a-d```: Conduct VPA for the sequence diversification of _fosX, mprF, lin, sul_.

```Supplementary Fig. 2```: Conduct multidimensional scaling (MDS) analysis for genomes with/without ARGs based on environmental conditions.\
```Supplementary Fig. 6a-b```: Compute paired two-sided t-test for predicted outputs from BIGSdb-Lm and CARD and present it using barplots.\
```Supplementary Fig. 7```: Compute the Spearman correlation between diversity and richness of functional ARGs.
