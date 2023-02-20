---
title: "Deformation field correction for spatial normalization of PET images using a population-derived partial least squares model"
collection: publications
permalink: /publication/2014-01-01-Deformation-field-correction-for-spatial-normalization-of-PET-images-using-a-population-derived-partial-least-squares-model
date: 2014-01-01
venue: 'Lecture Notes in Computer Science (8679), Machine Learning in Medical Imaging (MLMI)'
paperurl: 'http://link.springer.com/chapter/10.1007/978-3-319-10581-9_25'
citation: ' Murat Bilgel,  Aaron Carass,  Susan Resnick,  Dean Wong,  Jerry Prince, &quot;Deformation field correction for spatial normalization of PET images using a population-derived partial least squares model.&quot; Lecture Notes in Computer Science (8679), Machine Learning in Medical Imaging (MLMI), 2014.'
doi: 10.1007/978-3-319-10581-9_25
---

### Abstract

Spatial normalization of positron emission tomography (PET) images is essential for population studies, yet work on anatomically accurate PET-to-PET registration is limited. We present a method for the spatial normalization of PET images that improves their anatomical alignment based on a deformation correction model learned from structural image registration. To generate the model, we first create a population-based PET template with a corresponding structural image template. We register each PET image onto the PET template using deformable registration that consists of an affine step followed by a diffeomorphic mapping. Constraining the affine step to be the same as that obtained from the PET registration, we find the diffeomorphic mapping that will align the structural image with the structural template. We train partial least squares (PLS) regression models within small neighborhoods to relate the PET intensities and deformation fields obtained from the diffeomorphic mapping to the structural image deformation fields. The trained model can then be used to obtain more accurate registration of PET images to the PET template without the use of a structural image. A cross validation based evaluation on 79 subjects shows that our method yields more accurate alignment of the PET images compared to deformable PET-to-PET registration as revealed by 1) a visual examination of the deformed images, 2) a smaller error in the deformation fields, and 3) a greater overlap of the deformed anatomical labels with ground truth segmentations.

[Access paper here](http://link.springer.com/chapter/10.1007/978-3-319-10581-9_25){:target="_blank"}
