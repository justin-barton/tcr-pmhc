# TCR-pMHC
### A deep learning network for prediction of  TCR-pMHC binding

For exposition purposes, the entire pipeline has been laid out in a series of iPython notebooks:

Notebook | Contents
------------ | -------------
[1-data-prep.ipynb](1-data-prep.ipynb) | Data transformation and filtering
[2-data-split-tcr.ipynb](2-data-split-tcr.ipynb) | Generating negative training examples by randomly mispairing TCRs and epitopes and train / test splitting of the data (ensuring mutual exclusivity in TCRs)
[3-tcr2vec.ipynb](3-tcr2vec.ipynb) | Training a tcr2vec embedding model for TCRs using gensim
[4-model-tcr.ipynb](4-model-tcr.ipynb) | A Tensorflow implementation of the TCR-pMHC binding prediction model






