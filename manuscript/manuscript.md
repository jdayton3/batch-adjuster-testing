# Batch Correction Testing Framework

* Expression data often comes in different formats
* Batch adjusters often take data in different formats
* Batch adjusters are validated on nonstandard metrics and datasets
* Here we present a framework that
  * Runs batch adjusters with a common API
  * Accepts inputs as one of several common data formats
  * Calculates standard metrics
    * MSE
    * MMD
    * Classification accuracy (batch & true class)
    * Time taken
    * PCA (how much do the principal component loadings change?)
    * t-SNE
  * Uses standard datasets
    * bladderbatch
    * MNIST + artificial adjustment
    * GSE37199
    * TCGA - remove cancer type
    * One more? SeqC on GEO (data integration)?
  * Is able to be expanded (run & test on different datasets, different metrics)

Make it reproducible, put all files (even latex) in the same place
Try codeocean?
