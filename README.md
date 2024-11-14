Note that in this repo there is only code, and no datasets and graph indices (too heavy)

This is readme file for the git of PaperFeedback

Directory guide:

* Utils - Contains python notebook for embedding the datasets using sentence-bert, and creating pseudo-labels for GNN node-classification using embeddings and clustering

* Models - Contains setup for initial ANN retrieval pipeline, as well as code for training and inference of GNN models on graphs created from datasets

* Graphs - Contains code for creating edge indices and node indices for graphs based on several heuristics

* Evaluation - Contains code for the retrieval pipeline and evaluation methods for it

The dataset we used, ACM-citation-v8 can be accessed here: https://www.aminer.cn/citation
