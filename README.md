# MED263_Group4_scVelo_tutorial

## Team Members
Shreyas Labhsetwar, Daniel Sabater Minarim, Kevin Li


## Software
Students will need to install
-	scVelo, which is used mainly to create RNA velocity models for single-cell data (Weiler et al., 2023)
-	pandas, which is used to process and analyze data structures in Python (Pandas dev team, 2024).
-	python-igraph, which is used to help analyze and manipulate any network graphs (Csardi & Nepusz, 2006).
  
These packages are available in Python 3.6+ and can be installed using the pip package:

````
pip install -U scvelo
pip install -U pandas
pip install -U python-igraph
````

If students don’t have the pip package, the developers of scVelo recommend installing Miniconda beforehand.


## Dataset
The dataset being used is included within the scVelo package as scvelo.datasets.pbmc68k() and consists of 68,000+ peripheral blood mononuclear cells (PBMC) measured using tools provided by 10X Genomics. More information can be found in this paper (Zheng et al., 2017).
It should be noted that using this provided dataset skips several steps associated with generating input files for scVelo. While you do not need to download these tools, it is recommended that you look into the cellranger pipeline, the Loupe Browser program, and the velocyto pipeline if you were to use your own single-cell dataset.

## Tutorial Notebook

https://colab.research.google.com/drive/1QewjqEp5E0wGsv-EzxrvBtfsTB-nGp38?usp=sharing

## Presentation

https://docs.google.com/presentation/d/170XrTOhIlmuNSUoZvnK4hg3F-oSRoqokHctfyleEF1E/edit?usp=sharing

## Report

https://docs.google.com/document/d/1aqlELdQ0Z0uHza8UPUSjXCRSeVXCmkEzi6JOGkoumI8/edit?usp=sharing

## References

1. Csardi, G., & Nepusz, T. (2006). The igraph software package for complex network research. InterJournal, Complex Systems, 1695.
2. The pandas development team. (2024). pandas-dev/pandas: Pandas (v2.2.1). Zenodo. https://doi.org/10.5281/ZENODO.3509134
3. Weiler, P., Lange, M., Klein, M., Pe’er, D., & Theis, F. J. (2023). Unified fate mapping in multiview single-cell data. Cold Spring Harbor Laboratory. https://doi.org/10.1101/2023.07.19.549685
4. Zheng, G. X. Y., Terry, J. M., Belgrader, P., Ryvkin, P., Bent, Z. W., Wilson, R., Ziraldo, S. B., Wheeler, T. D., McDermott, G. P., Zhu, J., Gregory, M. T., Shuga, J., Montesclaros, L., Underwood, J. G., Masquelier, D. A., Nishimura, S. Y., Schnall-Levin, M., Wyatt, P. W., Hindson, C. M., … Bielas, J. H. (2017). Massively parallel digital transcriptional profiling of single cells. In Nature
Communications (Vol. 8, Issue 1). Springer Science and Business Media LLC. https://doi.org/10.1038/ncomms14049
