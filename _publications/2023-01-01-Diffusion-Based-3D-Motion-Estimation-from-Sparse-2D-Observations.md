---
title: "Diffusion-Based 3D Motion Estimation from Sparse 2D Observations"
authors: Niklas Gunnarsson, Jens Sjölund, Peter Kimstrand, Thomas Schön
collection: publications
category: preprints
permalink: /publication/2023-01-01-Diffusion-Based-3D-Motion-Estimation-from-Sparse-2D-Observations
abstract: Intra-interventional imaging is a tool for monitoring and guiding ongoing treatment sessions. Ideally one would like the full 3D image at high temporal resolution, this is however not possible due to the acquisition time. In this study, we consider the scenario when the observations are sparse and consist only of 2D image slices through the 3D volume. Given 2D-2D image registrations between a predefined 3D volume and the observations, we propose a method to estimate the full 3D motion. This 3D motion enables the reconstruction of the 3D anatomy. Our method relies on a conditioning-based denoising diffusion model and generates estimates given the 2D sparse observations. We reduce the dimensionality of the diffusion process by embedding the data in a lower dimensional space using principal component analysis. The model is evaluated in two experiments; first on synthetically generated data and then using medical lung images. Our observations show that the estimates are stable across the entire volume and within 1mm of the lower bound defined by the reconstruction error.
keywords: Motion modeling, 3D reconstruction, Medical image registration, Diffusion model
date: 2023-01-01
venue: 'Preprint'
paperurl: 'https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4673120'
codeurl: 'https://github.com/ngunnar/Diffusion3DMapper'
citation: ' Niklas Gunnarsson,  Jens Sjölund,  Peter Kimstrand,  Thomas Schön, &quot;Diffusion-Based 3D Motion Estimation from Sparse 2D Observations.&quot; Preprint, 2023.'
---