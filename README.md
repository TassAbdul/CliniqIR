# CliniqIR: Unsupervised Diagnostic Decision Support via Information Retrieval
Code for the paper Unsupervised Diagnostic Decision Support via Information Retrieval


## Datasets
1. Download [PubMed Abstracts](https://ftp.ncbi.nlm.nih.gov/pubmed/baseline/).

  ```
  rsync -Pav ftp.ncbi.nlm.nih.gov::pubmed/baseline/\*.xml.gz Pubmed/
  ```
  
2. Download [MIMIC-III datasets](https://mimic.mit.edu/docs/gettingstarted/).

## Requirements
1. [QuickUMLS](https://github.com/Georgetown-IR-Lab/QuickUMLS)

## Credits
Some of the structure in this repo was adopted from https://github.com/ziy/medline-indexer


## Reference
1. Luca Soldaini and Nazli Goharian. "QuickUMLS: a fast, unsupervised approach for medical concept extraction." MedIR Workshop, SIGIR 2016.
