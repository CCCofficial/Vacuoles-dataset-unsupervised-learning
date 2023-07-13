# Vacuoles-dataset-unsupervised-learning

This repository contains the dataset released in the paper entitled: "An unsupervised learning approach to resolve phenotype to genotype mapping in budding yeasts vacuoles" by V.P. Pastore, P.D. Alfano, A. Oke, S. Capponi, D. Eltanan, X. Woodruff-Madeira, A. Nguyen, J.C. Fung, and S. Bianco, accepted in the ICIAP2023 conference. 

The dataset is downloadable as a zip file, and contains:

+ hand_crafted_features:
    + test: test hand-crafted features divided into folders corresponding to ground truth annotations;
    + train_annotated: train hand-crafted features divided into folders corresponding to ground truth annotations;
    + train_clustershcf: train hand-crafted features divided into folders corresponding to clusters assigned using such features, as described in the paper;
+ images:
    + test: test images divided into folders corresponding to ground truth annotations;
    + train_annotated: train images divided into folders corresponding to ground truth annotations;
    + train_clustershcf: train images divided into folders corresponding to clusters assigned using hand-crafted features, as described in the paper;
 
Each image is encoded as RGB, with 80x80 pixels resolution. 
