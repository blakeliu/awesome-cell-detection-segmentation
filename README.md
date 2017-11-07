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
###  2.CNN
*  HEp-2 Cell Image Classification with Deep Convolutional Neural Networks.2014[[paper](https://www.researchgate.net/publication/267810644_HEp-2_Cell_Image_Classification_with_Deep_Convolutional_Neural_Networks)]
*  Accurate classification of protein subcellular localization from high throughput microscopy images using deep learning. 2016[[paper](https://www.biorxiv.org/content/biorxiv/early/2016/04/28/050757.full.pdf)]
*  A Guided Spatial Transformer Network for Histology Cell Differentiation. 2017[[paper](https://www.researchgate.net/publication/318721270_A_Guided_Spatial_Transformer_Network_for_Histology_Cell_Differentiation)]
*  Transitioning between Convolutional and Fully Connected Layers in Neural Networks. 2017[[paper](https://arxiv.org/pdf/1707.05743.pdf)]
##  Detection
###  1.CNN
*  Mitosis Detection in Breast Cancer Histology Images with Deep Neural Networks. miccai 2013[[paper](http://people.idsia.ch/~ciresan/data/miccai2013.pdf)][[code](https://github.com/znck/mitosis-detection.git)]
*  Deep Learning Based Automatic Immune Cell Detection for Immunohistochemistry Images. 2014[[paper](https://www.cise.ufl.edu/~tichen/pdf/miccai2014wsa.pdf)]
*  Microscopy cell counting and detection with fully convolutional regression networks. 2015[[paper](https://www.robots.ox.ac.uk/~vgg/publications/2015/Xie15/weidi15.pdf)][[code](https://github.com/WeidiXie/cell_counting_v2.git)]
*  Beyond Classification Structured Regression for Robust Cell Detection Using Convolutional Neural Network. 2015[[paper](https://www.researchgate.net/publication/305193695_Beyond_Classification_Structured_Regression_for_Robust_Cell_Detection_Using_Convolutional_Neural_Network)]
*  Cell Counting by Regression Using Convolutional Neural Network. 2016[[paper](https://www.researchgate.net/publication/308278424_Cell_Counting_by_Regression_Using_Convolutional_Neural_Network)]
*  Deep Convolutional Neural Networks for Human Embryonic Cell Counting. 2016[[paper](http://users.cecs.anu.edu.au/~sgould/papers/bic16-embryo.pdf)]
*  Deep Learning for Imaging Flow Cytometry:Cell Cycle Analysis of Jurkat Cells. 2016[[paper](https://www.biorxiv.org/content/early/2016/10/17/081364)]
*  AggNet: Deep Learning From Crowds for Mitosis Detection in Breast Cancer Histology Images. 2016[[paper](https://www.researchgate.net/publication/294108292_AggNet_Deep_Learning_From_Crowds_for_Mitosis_Detection_in_Breast_Cancer_Histology_Images)]
*  Locality Sensitive Deep Learning for Detection and Classification of Nuclei in Routine Colon Cancer Histology Images. 2016[[paper](http://ieeexplore.ieee.org/document/7399414/?reload=true)]
*  Deep Learning for Identifying Metastatic Breast Cancer. 2016[[paper](https://arxiv.org/pdf/1606.05718.pdf)]
*  Detecting Cancer Metastases on Gigapixel Pathology Images. 2017 google[[paper](http://patologi.com/Detecting%20Cancer%20Metastases%20on%20Gigapixel%20Pathology%20Images.pdf)]
*  Large scale tissue histopathology image classification, segmentation, and visualization via deep convolutional activation features. 2017[[paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5446756/pdf/12859_2017_Article_1685.pdf)]
*  MDNet: A Semantically and Visually Interpretable Medical Image Diagnosis Network. CVPR 2017[[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_MDNet_A_Semantically_CVPR_2017_paper.pdf)][[code](https://github.com/zizhaozhang/mdnet-cvpr2017/)]

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
*  Cell Segmentation Proposal Network For Microscopy Image Analysis. 2016[[paper](https://users.aalto.fi/~kannalj1/publications/dlmia2016.pdf)]
*  DCAN Deep Contour-Aware Networks for Accurate Gland Segmentation. CVPR 2016[[paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Chen_DCAN_Deep_Contour-Aware_CVPR_2016_paper.pdf)]
*  Constrained Deep Weak Supervision for Histopathology Image Segmentation. 2017[[paper](https://arxiv.org/pdf/1701.00794.pdf)]
###  2.Level Set
*  Automated Nucleus and Cytoplasm Segmentation of Overlapping Cervical Cells. 2013[[paper](https://www.researchgate.net/publication/260127853_Automated_Nucleus_and_Cytoplasm_Segmentation_of_Overlapping_Cervical_Cells9)][[code](https://github.com/luzhi/miccai2013)]
*  An Improved Joint Optimization of Multiple Level Set Functions for the Segmentation of Overlapping Cervical Cells. 2015[[paper](https://www.researchgate.net/publication/270966398_An_Improved_Joint_Optimization_of_Multiple_Level_Set_Functions_for_the_Segmentation_of_Overlapping_Cervical_Cells)][[code](https://github.com/luzhi/cellsegmentation_TIP2015)]


## SoftWare
*  CellProfiler[link(http://cellprofiler.org/)]
*  CellProfiler Analyst[link(http://cellprofiler.org/cp-analyst/)]
