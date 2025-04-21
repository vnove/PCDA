**Author**
V. Novellus Washington | vnwashington@oakland.edu

**Single-Cell RNA-Seq Analysis of E18 Mouse Brain: Cell Type Mapping and Gene Expression Prediction - COLORS IN MOLECULAR BIOLOGY"**

**Introduction**

For my Type II final project, I used python tools such as Scanpy (Single cell Analysis), Matplotlib (plotting), seaborn (plotting), numpy (data analysis), anndata (data analysis), pandas (data analysis), scklearn (machine learning) to analyze and visualize single cell data (RNAseq) to understand individual cells to build a mapping of different cell types in the data set of an Embryonic 18 Day Mouse Brain. The dataset contains single cell data of 1,000 different cells.

After cluster classification, I used a decision tree, a machine learning architect, to predict the expression of a selected marker gene; using logistical regression to select a list of genes. I measured the models accuracy, precision, recall, and a validation curve to quantify and understand the models performance. As a tertiary part to the project, I used a random forest classifier, another machine learning architecture, to predict the cluster names based on gene expression across all cells. I evaluated the models performance by checking its prediction against the actual names, identified the miscalls and correct calls, confusion matrix, precision, recall, f1, and accuracy.    

This is a Single Cell Analysis of collected RNA data from the brain of an 18 Day Old Embryonic Mus musculus (House Mouse). The data is publicly available, it was collected from 10X Genomics database website (https://www.10xgenomics.com/datasets/fresh-embryonic-e-18-mouse-brain-5-k-1-standard-2-0-0).  



**Instructions to Run**

1. The code is very straightforward, all you have to do is run through each kernel that contains code.
2. For the first kernel in the **Data Retrieval and Exploratory Data Analysis**, if you already have a folder named Data, please change the output for the command "!mkdir -p data" to a folder name of your choice. 

**Project Goals**

This project aims to identify distinct cell populations within the E18 mouse brain and predict marker gene expression patterns to better understand cellular identity.

**Key Outputs**
- Mean Variance Plot (#15)
- Gene graph (#20)
- UMAP Gene Expression (#25)
- Gene Expression dot plot (#37)
- Gene Expression Heatmap (#38)
- Renamed Clusters (#40)
- Evaluation of Decision Tree (#52)
- Decision Tree (#53)
- Predicted Cluster Names (#61)
- Prediction Results for the Random Forest Classifier (#63)
