# Single Cell Analysis Project 
The data used is from the following study: https://doi.org/10.1016/j.molcel.2021.10.013. Data was down- loaded from GEO using the following accession number: GSE173682.
Specifically, we are focusing on an endometrial cancer tumor that metastasized to the ovary in a human patient. The dataset contains nearly 6000 genes.
## File Structure 
- PDFs : Output PDFs of analysis
    - Main_analysis.pdf: This file is the PDF report from the Rmarkdown.  
    - scVI_clustering.pdf: This file is the PDF report from the JupyterNotebook.  
- Notebooks: Notebook's used for analysis. 
    - Main_analysis.rmd: This file contains the majority of the scRNA-seq processing, including an InferCNV analysis.  
    - scVI_clustering.ipynb: This file contains an additional analysis of clustering the same data using scVI.
    