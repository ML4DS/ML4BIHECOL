# ML4BIHECOL

Machine learning tools for the analysis of large document collections. A brief description of each of them is given, even though each has it's own documentation.

The available repositories, divided by tasks are:

Spark implementation of parallel algorithms:
- [**DistributedCWLM**:](https://github.com/jperdel/DistributedCWLM/tree/a8cac560c79c51e06c44a3ce3978f0c6a67423fa) distributed, interpretable regression algorithm in Spark.
- **SVM_spark**: distributed, non-linear, semiparametric SVM implementation in Spark.
- [**pysparkMVA**](https://github.com/jeroarenas/pysparkMVA/tree/481e1f48c3d42308414ea21b5ef4e56b580cf914): distributed implementation of Deep Learning for Margin Valuation Adjustment with regularization.

Topic Models tools:
- [**TMtweets**](https://github.com/jperdel/TMtweets/tree/1189b613b39498c86254df0ebd57a5d65a0805e1): topic modeling pipeline. Designed to work with tweets, but can be extended to other documents.
- [**labelFactory**](https://github.com/Orieus/labelFactory/tree/3684d96261c5af585a7b58f4ba9c5b6487a00637): a generic application for labelling a subset of sites in a web site collection, or a subset of docs in a text collection.
- [**one_def_classification**](https://github.com/Orieus/one_def_classification/tree/3269290e1fa06ec104a38810c5dffa5401f34ef1): dataless text classification using definitions as labeled data.
- [**WeakLabelModel**](https://github.com/Orieus/WeakLabelModel/tree/7d51fc719b8d5a715b55587e382f84b87c54378a): a library for training multiclass classifiers with weak labels.

Integration of modules:
- [**PTL_data**](https://github.com/jeroarenas/PTL_data/tree/ee94fc4c3d9be8753e60868f31ef7672e071a407): ETL & lemmatization tool for PTL.
- [**PdbManager**](https://github.com/Grarck/PdbManager/tree/89b3a405e412ca2121d37512c71359b6a2d22e4f): Managing mySQL databases (replaces older DB_expl).
- [**dbManager**](https://github.com/jeroarenas/dbManager/tree/dd0b89870a204377f3bf862368c684f9c6fd3325): Python class for managing mySQL or sqlite databases.
- [**menuNavigator**](https://github.com/Orieus/menuNavigator/tree/dcbcafefd9c71a7257edcfca586a7f40bd52b6b5): a generic template application to generate command-line menus.

Feature Selection and Feature Extraction: 
- [**regMVA**](https://github.com/sevisal/regMVA/tree/cc886540ffea21c13e444a80aedeba6bdba7920b): Deep Learning for Margin Valuation Adjustment with regularization.
- [**SSHIBA**](https://github.com/sevisal/SSHIBA/tree/9a57305928970b4757229aae709c2e656efb05ae): generalized Bayesian approach to feature extraction for heterogeneous data.
- [**KSSHIBA**](https://github.com/sevisal/KSSHIBA/tree/9919b43c3e3bb0f1115e894b3891224e2a7985c8): kernelized observation SSHIBA.

Graph synthesis, processing and analysis.
- [**supergraph**](https://github.com/Orieus/supergraph/tree/9132c318da8a3f48a859887555532d5cfa5dbad7): a software package for the synthesis, analysis and processing of large graphs.

## Instructions:

To clone the project with all their submodules:

    git clone --recurse-submodules https://github.com/ML4DS/ML4BIHECOL

If you have already done

    git clone https://github.com/ML4DS/ML4BIHECOL

you can do 

    git submodule update --init --recursive
    
Alternatively, you can use specific submodules only. The best way to work with a specific submodule is to clich pon the l

Project funded by: FEDER/Ministerio de Ciencia, Innovación y Universidades – Agencia Estatal de Investigación/ _Proyecto TEC2017-83838-R.

<img src="https://github.com/ML4DS/ML4BIHECOL/blob/main/figs/logos_ciencia.jpg" width="400">






