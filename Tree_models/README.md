# Tree models

The aim of this study is to predict the overall_survival that specify if the patient is alive or dead. This
will be done by three models (tree, a random forest and gradient boosting in the packege adaboost).

### Data

The Molecular Taxonomy of Breast Cancer International Consortium (METABRIC) database is a CanadaUK Project which contains targeted sequencing data of 1,980 primary breast cancer samples. Clinical and
genomic data was downloaded from cBioPortal. The dataset was collected by Professor Carlos Caldas from
Cambridge Research Institute and Professor Sam Aparicio from the British Columbia Cancer Centre in
Canada and published on Nature Communications (Pereira et al., 2016)..
Metabric dataset integrates three types of data. Clinical data are in columns 1 to 31, gene expression data
are in columns 32 to 520, mutation data are in columns 521 to 693. Gene expression values are normalized
to be z-score.
The data set has 1904 observations on 693 variables.
