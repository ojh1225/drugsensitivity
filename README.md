# Pan-cancer prediction of cell line-drug sensitivity using network-based methods

<img src="img/Figure1A.png" width="600">

For clustering of cell lines, the gene expression profiles for 915 cell lines were analyzed on the HPRD network. Invariant measures for individual nodes were then computed, and the Wasserstein distance (EMD) was computed between each pair of cell lines on the network. Lastly, hierarchical clustering was performed on the resultant Wasserstein distance matrix. For clustering of drugs, we obtained the cheminformatic features of 200 drugs, and built a data-driven network of cheminformatic features using the graphical LASSO. Similar to cell lines, hierarchical clustering was performed on the resultant Wasserstein distance matrix. 


<img src="img/Figure1B.png" width="600">
A random forest model was built on each paired cluster of cell lines and drugs to predict drug responses in log(IC50) values. 


Data
1. Supplement.xlsx: Detailed information of cell lines and drugs as well as clustering results are shown. 
