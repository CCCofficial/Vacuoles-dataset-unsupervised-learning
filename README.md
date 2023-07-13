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


<p align="center">
<img width="299" alt="image_repo"  src="https://github.com/CCCofficial/Vacuoles-dataset-unsupervised-learning/assets/51142446/64c68e99-bb84-4d2d-893e-bb97de1bffab"><br>
    <i>Representative vacuole images of the $4$ classes present in the dataset A) single, B) multiple, C) condensed vacuole, and D) negative or dead cell</i>

</p>


    
