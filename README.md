# ML4BIHECOL

Machine learning tools for the analysis of large document collections. A brief description of each of them is given, even though each has it's own documentation.

The available repositories, divided by tasks are:

Spark implementation of parallel algorithms:
- DistributedCWLM: distributed, interpretable regression algorithm in Spark.
- SVM_spark: distributed, non-linear, semiparametric SVM implementation in Spark.
- pysparkMVA: distributed implementation of Deep Learning for Margin Valuation Adjustment with regularization.

Topic Models tools:
- TMtweets: topic modeling pipeline. Designed to work with tweets, but can be extended to other documents.
- labelFactory: a generic application for labelling a subset of sites in a web site collection, or a subset of docs in a text collection.
- one_def_classification: dataless text classification using definitions as labeled data.
- WeakLabelModel: a library for training multiclass classifiers with weak labels.

Integration of modules:
- PTL_data: ETL & lemmatization tool for PTL.
- DB_expl: Exploratory Data Analysis of mySQL databases.
- dbManager: Python class for managing mySQL or sqlite databases.
- menuNavigator: a generic template application to generate command-line menus.

Feature Selection and Feature Extraction: 
- regMVA: Deep Learning for Margin Valuation Adjustment with regularization.
- SSHIBA: generalized Bayesian approach to feature extraction for heterogeneous data.
- KSSHIBA: kernelized observation SSHIBA.
