# Unsupervised-clustering-of-18F-Florbetapir-AV45-PET-studies-in-Alzheimer-disease
This study focuses on Alzheimer’s disease analysis
by applying voxel-based clustering algorithms to PET brain
imaging data. The dataset consists of 65 baseline 18F-Florbetapir
(AV45) PET scans from the Mild Cognitive Impairment group
of the Alzheimer’s Disease Neuroimaging Initiative (ADNI).
This study aims to uncover unique patterns in Alzheimer’s
disease development through unsupervised voxel-based clustering
methods. The focal point of this project is the voxel processing in PET images and the utilization of a predefined atlas
to pinpoint Regions of Interest (ROIs). This process involves
converting 3D PET scans into 1D arrays using Nibabel masking,
followed by application of Principal Component Analysis (PCA)
for dimensionality reduction. After this preparation phase, the
dataset was then subjected to hierarchical clustering, which
exposed unique patterns. Three notable clusters were formed.
Interestingly, the first cluster included most individuals that
tested positive for markers associated with Alzheimer’s disease.
However, all the scans in the third cluster were classified as
negative for these markers, indicating a profile that seemed in
good health. Interestingly, the second cluster had a mix of positive
and negative cases, indicating the potential presence of earlystage Alzheimer’s cases that might not be distinctly separable
from healthy brain scans.
<div align="center">
    <img src=" clustering of PET scans main/Hierarchical clustering.jpeg" alt="Alt text" title="Hover text" height="400" width="500"/>
    <p><em>Figure 1: Hierarchical clustering dendrogram with Wards Linkage method. 2 clusters.</em></p>
</div>
<div align="center">
    <img src=" clustering of PET scans main/Cluster.jpeg" alt="Alt text" title="Hover text" height="400" width="500"/>
    <p><em>Figure 2: Brain scans from each cluster – 2 Clusters</em></p>
</div>
<div align="center">
    <img src=" clustering of PET scans main/Hierarchical cluster_3.jpeg" alt="Alt text" title="Hover text" height="400" width="500"/>
    <p><em>Figure 3: Hierarchical clustering dendrogram with Wards Linkage method. 3 clusters.</em></p>
</div><div align="center">
    <img src=" clustering of PET scans main/Brain cluster_3.jpeg" alt="Alt text" title="Hover text" height="400" width="500"/>
    <p><em>Figure 4: Brain scans from each cluster – 3 Clusters</em></p>
</div>
