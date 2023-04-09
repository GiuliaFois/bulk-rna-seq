# EdgeR Bulk RNA-seq analysis

This repository contains one of the two projects for my Transcriptomics exam I took as part of my "Bioinformatics for Computational Genomics" MSc at University of Milano.

The purpose of this project was carrying out a Bulk RNA-Seq analysis over genes expression data coming from 3 different tissues. The steps included sample selection, differential expression analysis (carried out mainly through the Bioconductor [edgeR](https://bioconductor.org/packages/release/bioc/html/edgeR.html) package) and functional enrichment (executed through the [Enrichr](https://maayanlab.cloud/Enrichr/) web interface on the differential analysis result genes).
The three count tables, from which the samples have been extracted from, come from the [Recount](http://rna.recount.bio/) publicly available repository and can be found in the _data/_ folder.


Other than the R source code, included in the _bulkRNA\_analysis.Rmd_ file with some brief explanation about each section, the slides I showed as my final presentation are available as a pptx file.
