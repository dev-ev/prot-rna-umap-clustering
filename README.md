# prot-rna-umap-clustering
Joint UMAP embedding and clustering of proteomic and transcriptomic data.

Developed by Egor Vorontsov with educational purposes.

The notebook was created in Jupyter Lab on Windows with Python 3.8. The workflow depends on third-party libraries that can be installed with pip:<br>
    pip intsall scipy numpy pandas matplotlib seaborn scikit-learn umap-learn.
  
 The data is taken from the [article by Hultqvist *et al*](https://www.nature.com/articles/s41559-018-0568-5). The relative protein abundance table from the proteomic analysis can be found in the repository. The RPKM table from the transcriptomic experiment can be found at the [Gene Expression Omnibus (GEO) project page ](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE92601).

The project consisted of 10 samples of *Escherichia coli* cultures that belonged to 5 different conditions. Mass spectrometry-based proteomic and transcriptomic data has been acquired for each of the samples. The aim of this data processing workflow is to cluster the genes in an unsupervised fashion based on their profiles of change across both data sets.
