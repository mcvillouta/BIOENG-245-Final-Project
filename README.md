# BIOENG-245-Final-Project

Peripheral blood mononuclear cells (PBMCs) are a group of different cell types in our blood, a subset of what we call white blood cells. They include many important parts of our immune system: T cells, B cells, natural killer cells, and so on. These cells are responsible for our innate and adaptive immune responses. When we get infected or vaccinated, they kick into high gear. In different situations, or with different diseases, the mix of different cell types shifts and so does the gene expression within one type of cell. PBMCs can be isolated very easily from patient blood samples, just by spinning the blood in a centrifuge that separates different cell types by weight. So, looking at these cells can be very informative.

## Part 1: Lower-dimension representations of the cells

Starting from scRNA-seq data from PBMCs, I look at the cells in a lower-dimension space. Then, I implement an autoencoder to find a latent space representation of the data. Finally, I compare two-dimensional representations of the data using t-SNE, PCA, and the latent space defined by the autoencoder.

## Part 2: Classifier

I implement a model built on top of the encoder for classifying unlabeled cells as one of the cell types labeled in the original data. 
