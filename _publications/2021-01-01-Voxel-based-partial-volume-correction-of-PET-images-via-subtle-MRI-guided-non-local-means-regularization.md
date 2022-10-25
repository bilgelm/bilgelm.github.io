---
title: "Voxel-based partial volume correction of PET images via subtle MRI guided non-local means regularization"
collection: publications
permalink: /publication/2021-01-01-Voxel-based-partial-volume-correction-of-PET-images-via-subtle-MRI-guided-non-local-means-regularization
date: 2021-01-01
venue: 'Physica Medica'
paperurl: 'https://doi.org/10.1016/j.ejmp.2021.07.028'
citation: ' Yuanyuan Gao,  Yansong Zhu,  Murat Bilgel,  Saeed Ashrafinia,  Lijun Lu,  Arman Rahmim, &quot;Voxel-based partial volume correction of PET images via subtle MRI guided non-local means regularization.&quot; Physica Medica, 2021.'
doi: 10.1016/j.ejmp.2021.07.028
---

### Abstract

**Purpose:** Positron emission tomography (PET) images tend to be significantly degraded by the partial volume effect (PVE) resulting from the limited spatial resolution of the reconstructed images. Our purpose is to propose a partial volume correction (PVC) method to tackle this issue.

**Methods:** In the present work, we explore a voxel-based PVC method under the least squares framework (LS) employing anatomical non-local means (NLMA) regularization. The well-known non-local means (NLM) filter utilizes the high degree of information redundancy that typically exists in images, and is typically used to directly reduce image noise by replacing each voxel intensity with a weighted average of its non-local neighbors. Here we explore NLM as a regularization term within iterative-deconvolution model to perform PVC. Further, an anatomical-guided version of NLM was proposed that incorporates MRI information into NLM to improve resolution and suppress image noise. The proposed approach makes subtle usage of the accompanying MRI information to define a more appropriate search space within the prior model. To optimize the regularized LS objective function, we used the Gauss-Seidel (GS) algorithm with the one-step-late (OSL) technique.

**Results:** After the import of NLMA, the visual and quality results are all improved. With a visual check, we notice that NLMA reduce the noise compared to other PVC methods. This is also validated in bias-noise curve compared to non-MRI-guided PVC framework. We can see NLMA gives better bias-noise trade-off compared to other PVC methods.

**Conclusions:** Our efforts were evaluated in the base of amyloid brain PET imaging using the BrainWeb phantom and in vivo human data. We also compared our method with other PVC methods. Overall, we demonstrated the value of introducing subtle MRI-guidance in the regularization process, the proposed NLMA method resulting in promising visual as well as quantitative performance improvements.

**Highlights:**
- A voxel-based PVC method under the least squares framework (LS).
- An anatomical-guided NLM (NLMA) can improve resolution and suppress image noise.
- We use subtle usage of the accompanying MRI information to define the search space.
- We evaluated this method using the BrainWeb phantom and in vivo human data.

[Access paper here](https://doi.org/10.1016/j.ejmp.2021.07.028){:target="_blank"}
