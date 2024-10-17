---
title: "Unsupervised dynamic modeling of medical image transformations"
authors: Niklas Gunnarsson, Jens Sjölund, Peter Kimstrand, Thomas Schön
collection: publications
category: publications
permalink: /publication/2022-01-01-Unsupervised-dynamic-modeling-of-medical-image-transformations
abstract: Spatiotemporal imaging has applications in e.g. cardiac diagnostics, surgical guidance, and radiotherapy monitoring, In this paper, we explain the temporal motion by identifying the underlying dynamics, only based on the sequential images. Our dynamical model maps the inputs of observed high-dimensional sequential images to a low-dimensional latent space wherein a linear relationship between a hidden state process and the lower-dimensional representation of the inputs holds. For this, we use a conditional variational auto-encoder (CVAE) to nonlinearly map the higher dimensional image to a lower-dimensional space, wherein we model the dynamics with a linear Gaussian state-space model (LG-SSM). The model, a modified version of the Kalman variational auto-encoder, is end-to-end trainable, and the weights, both in the CVAE and LG-SSM, are simultaneously updated by maximizing the evidence lower bound of the marginal likelihood. In contrast to the original model, we explain the motion with a spatial transformation from one image to another. This results in sharper reconstructions and the possibility of transferring auxiliary information, such as segmentation, through the image sequence. Our experiments, on cardiac ultrasound time series, show that the dynamic model outperforms traditional image registration in execution time, to a similar performance. Further, our model offers the possibility to impute and extrapolate for missing samples
keywords: Ultrasonic imaging,Motion segmentation,Dynamics,Time series analysis,Surgery,State-space methods,Spatiotemporal phenomena,Dynamic system,State-space models,Deep learning,Generative models,Sequential modeling,Image registration
date: 2022-01-01
venue: 'In the proceedings of 25th International Conference on Information Fusion (FUSION)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9841369'
codeurl: 'https://github.com/ngunnar/med-dyn-reg'
citation: ' Niklas Gunnarsson,  Jens Sjölund,  Peter Kimstrand,  Thomas Schön, &quot;Unsupervised dynamic modeling of medical image transformations.&quot; In the proceedings of 25th International Conference on Information Fusion (FUSION), 2022.'
---