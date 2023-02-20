---
title: "Deformation field correction for spatial normalization of PET images"
collection: publications
permalink: /publication/2015-01-01-Deformation-field-correction-for-spatial-normalization-of-PET-images
date: 2015-01-01
venue: 'NeuroImage'
paperurl: 'https://doi.org/10.1016/j.neuroimage.2015.06.063'
citation: ' Murat Bilgel,  Aaron Carass,  Susan Resnick,  Dean Wong,  Jerry Prince, &quot;Deformation field correction for spatial normalization of PET images.&quot; NeuroImage, 2015.'
doi: 10.1016/j.neuroimage.2015.06.063
---

### Abstract

Spatial normalization of positron emission tomography (PET) images is essential for population studies, yet the current state of the art in PET-to-PET registration is limited to the application of conventional deformable registration methods that were developed for structural images. A method is presented for the spatial normalization of PET images that improves their anatomical alignment over the state of the art. The approach works by correcting the deformable registration result using a model that is learned from training data having both PET and structural images. In particular, viewing the structural registration of training data as ground truth, correction factors are learned by using a generalized ridge regression at each voxel given the PET intensities and voxel locations in a population-based PET template. The trained model can then be used to obtain more accurate registration of PET images to the PET template without the use of a structural image. A cross validation evaluation on 79 subjects shows that the proposed method yields more accurate alignment of the PET images compared to deformable PET-to-PET registration as revealed by 1) a visual examination of the deformed images, 2) a smaller error in the deformation fields, and 3) a greater overlap of the deformed anatomical labels with ground truth segmentations.

[Access paper here](https://doi.org/10.1016/j.neuroimage.2015.06.063){:target="_blank"}
