# Investigating the Expression Profiles of Different Stages of Glioma 

## Overview
This repository sets out the skeleton of an organizational structure used for scientific research. It loosely follows what I have used for several of my research projects and I hope it inspires you to conduct your research in an open, reproducible, and honest manner.

### **`experiments`** 
Contains ipynb files with all analysis code
1. _Dimension_Reduction.ipynb_ contains all code for dimension reduction analyses, including UMAP and PCA

### **`data`** 
Contains raw RNA-Seq data that was used in this analysis. Two files are present:
1. _unc.edu_GBM_IlluminaHiSeq_RNASeqV2.geneExp.tsv_ contains RNA-Seq data for glioblastoma tumors
2. _unc.edu_LGG_IlluminaHiSeq_RNASeqV2.geneExp.tsv_ contains RNASeq data for low grade glioma tumors.
Both datasets contain normalized counts and are derived from the TCGA dataset hosted on synapse.org (SynID: syn2812961). Unfortunately, the data source does not specify how counts were normalized.

# License Information

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="github.com/gchure/reproducible_research">
    <span property="dct:title">Griffin Chure</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">A template for using git as a platform for reproducible scientific research</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="US" about="github.com/gchure/reproducible_research">
  United States</span>.
</p>
