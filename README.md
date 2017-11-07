# Awesome-cell-detection-segmentation

Nucleus/cell detection and segmentation on microscopy images and digital pathology.

## Overview paper
*  Robust NucleusCell Detection and Segmentation in Digital Pathology and Microscopy Images A Comprehensive Review[[paper](http://europepmc.org/abstract/med/26742143)]
*  Computational Pathology: Challenges and Promises for Tissue Analysis.Thomas J. Fuchsa,b, Joachim M. Buhmann.2017[[paper](https://arxiv.org/pdf/1601.00027v1.pdf)]

##  Classification 
###  1.Auto-encoder
*  Classification of Histology Sections via Multispectral Convolutional Sparse Coding[[paper](https://www.researchgate.net/publication/264002179_Classification_of_Histology_Sections_via_Multispectral_Convolutional_Sparse_Coding)][[code](http://bmihub.org/project/multispectralcsc)]
*  Stacked Predictive Sparse Decomposition for Classification of Histology Sections. Hang Chang. 2015[paper](https://www.researchgate.net/publication/276540095_Stacked_Predictive_Sparse_Decomposition_for_Classification_of_Histology_Sections)[[code](http://bmihub.org/project/stackedpsd)]
*  Robust Cell Detection and Segmentation in Histopathological Images Using Sparse Reconstrcution and Stacked Denoising Autoencoders. MICCAI15 [[paper](https://webpages.uncc.edu/~szhang16/paper/MICCAI15_autoencoder.pdf)]
*  Robust Cell Detection of Histopathological Brain Tumor Images Using Sparse Reconstruction and Adaptive Dictionary Selection 2016[[paper](https://www.researchgate.net/publication/291425171_Robust_Cell_Detection_of_Histopathological_Brain_Tumor_Images_Using_Sparse_Reconstruction_and_Adaptive_Dictionary_Selection)]
*  Sparse Autoencoder for Unsupervised Nucleus Detection and Representation in Histopathology Images. [[paper](https://arxiv.org/abs/1704.00406)]

##  Detection
###  1.CNN

###  2.Random_forest
*  Learning-based mitotic cell detection in histopathological images. 2012 [[paper](https://hciweb.iwr.uni-heidelberg.de/sites/default/files/node/files/2081404558/sommer_12_learning-based.pdf)]
> * method: random forest classify object and non-object, and svm classify last.

*  You Should Use Regression to Detect Cells. Philipp KainzMartin Urschler.In MICCAI. 2015.[[paper](https://pdfs.semanticscholar.org/99da/f0b8c7a3880d34acff7bc7b370fc7e8a4cf1.pdf)][[code](https://github.com/pkainz/MICCAI2015)]
> * Methd: ACF feature, sliding window, random trees regression.
### 3.SVM
*  Learning to detect cells using non-overlapping extremal regions. 2012.[[paper](http://www.robots.ox.ac.uk/~vilem/miccai2012.pdf)][[code](http://www.robots.ox.ac.uk/~vgg/research/cell_detection/)]
> * Method: MSER,DP,structure SVM.

### 4.CRF
*   Heterogeneous Conditional Random Field_ Realizing Joint Detection and Segmentation of Cell Regions in Microscopic Images. cvpr2010.[[paper](http://www.albany.edu/celltracking/papers/Heterogeneous-Conditional-Random.pdf)]



## Segmentation
###  1.CNN
*  Nuclei Segmentation via Sparsity Constrained Convoluational Regression. 2015[[paper](https://www.researchgate.net/publication/280660145_Nuclei_Segmentation_via_Sparsity_Constrained_Convolutional_Regression)][[code](http://bmihub.org/project/sccr)]
###  2.Level Set
*  Automated Nucleus and Cytoplasm Segmentation of Overlapping Cervical Cells. 2013[[paper](https://www.researchgate.net/publication/260127853_Automated_Nucleus_and_Cytoplasm_Segmentation_of_Overlapping_Cervical_Cells9)][[code](https://github.com/luzhi/miccai2013)]
*  An Improved Joint Optimization of Multiple Level Set Functions for the Segmentation of Overlapping Cervical Cells. 2015[[paper](https://www.researchgate.net/publication/270966398_An_Improved_Joint_Optimization_of_Multiple_Level_Set_Functions_for_the_Segmentation_of_Overlapping_Cervical_Cells)][[code](https://github.com/luzhi/cellsegmentation_TIP2015)]


## SoftWare
*  CellProfiler[link(http://cellprofiler.org/)]
*  CellProfiler Analyst[link(http://cellprofiler.org/cp-analyst/)]
