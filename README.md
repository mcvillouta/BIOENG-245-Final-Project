# BIOENG-245-Final-Project

## Part 1: Lower-dimension representations of the cells

Starting from scRNA-seq data from Peripheral blood mononuclear cells (PBMCs), I look at the cells in a lower-dimension space. Then, I implement an autoencoder to find a latent space representation of the data. Finally, I compare two-dimensional representations of the data using t-SNE, PCA, and the latent space defined by the autoencoder.

## Part 2: Classifier

I implement a model built on top of the encoder for classifying unlabeled cells as one of the cell types labeled in the original data. 
