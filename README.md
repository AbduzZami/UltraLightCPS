# UltraLightCPS
This work is published in Biomedical Signal Processing and Control Journal

# Abstract 
Colorectal cancer remains a major global health concern, with early detection and treatment of colorectal polyps playing a critical role in prevention. Although colonoscopy is the gold standard for polyp detection, human limitations—such as fatigue and visual ambiguities stemming from the diverse morphology of polyps and low contrast—lead to substantial miss rates. This underscores the urgent need for intelligent, automated support systems to enhance diagnostic accuracy and consistency. Deep learning-based medical image segmentation has shown promise in this domain; however, the large model sizes and high computational complexity of existing methods hinder their deployment in real-time and resource-constrained clinical settings. To address this, we propose UltraLightCPS, a novel colon polyp segmentation model that achieves high segmentation accuracy with ultra-low computational overhead. With only 0.23 million parameters, UltraLightCPS incorporates an adaptive multi-scale semantic fusion mechanism that enhances feature extraction, refinement, and integration. The encoder utilizes depthwise separable convolutions for efficient hierarchical feature extraction, while a compressed multi-scale feature module captures diverse polyp shapes and sizes. The decoder integrates high- and low-level features through a global semantic assembly strategy, enabling precise segmentation of irregular boundaries. UltraLightCPS achieves a Dice score of 92.58% on the CVC-ClinicDB dataset, requiring only 0.08 GFlops and delivering an inference speed of 113.73 frames per second. This positions UltraLightCPS as an efficient solution for real-time, edge-based clinical deployment, establishing a new benchmark in lightweight and accurate polyp segmentation for colorectal cancer screening.


# Paper Link
https://www.sciencedirect.com/science/article/pii/S1746809426007160


# Dataset Link
This contains all the datasets used in this paper.
https://www.kaggle.com/datasets/abduzzami/colon-datasets

References of the datasets

[CVC-ClinicDB] D. Jha, P. H. Smedsrud, M. A. Riegler, P. Halvorsen, T. De Lange, D. Johansen, H. D. Johansen, Kvasir-seg: A segmented polyp dataset, in: International conference on multimedia modeling, Springer, 2019, pp. 451–462. 33

[CVC-ColonDB] J. Bernal, F. J. Sánchez, G. Fernández-Esparrach, D. Gil, C. Ro- dríguez, F. Vilariño, Wm-dova maps for accurate polyp highlighting in colonoscopy: Validation vs. saliency maps from physicians, Comput- erized medical imaging and graphics 43 (2015) 99–111.

[Kvasir-SEG] N. Tajbakhsh, S. R. Gurudu, J. Liang, Automated polyp detection in colonoscopy videos using shape and context information, IEEE trans- actions on medical imaging 35 (2015) 630–644.


# Cite This Article
```bibtex
@article{ZAMI2026110162,
title = {UltraLightCPS: An Ultra-Lightweight Colon Polyp Segmentation model using an adaptive compressed multi-scale semantic fusion mechanism},
journal = {Biomedical Signal Processing and Control},
volume = {120},
pages = {110162},
year = {2026},
issn = {1746-8094},
doi = {https://doi.org/10.1016/j.bspc.2026.110162},
url = {https://www.sciencedirect.com/science/article/pii/S1746809426007160},
author = {Abduz Zami and Shadman Sobhan and Mohiuddin Ahmed and Md Palash Uddin},
keywords = {Colon polyp segmentation, Lightweight model, Medical image segmentation, Colorectal cancer, Real-time inference, Multi-scale feature extraction, Semantic fusion, Deep learning},
abstract = {Colorectal cancer remains a major global health concern, with early detection and treatment of colorectal polyps playing a critical role in prevention. Although colonoscopy is the gold standard for polyp detection, human limitations—such as fatigue and visual ambiguities stemming from the diverse morphology of polyps and low contrast—lead to substantial miss rates. This underscores the urgent need for intelligent, automated support systems to enhance diagnostic accuracy and consistency. Deep learning-based medical image segmentation has shown promise in this domain; however, the large model sizes and high computational complexity of existing methods hinder their deployment in real-time and resource-constrained clinical settings. To address this, we propose UltraLightCPS, a novel colon polyp segmentation model that achieves high segmentation accuracy with ultra-low computational overhead. With only 0.23 million parameters, UltraLightCPS incorporates an adaptive multi-scale semantic fusion mechanism that enhances feature extraction, refinement, and integration. The encoder utilizes depthwise separable convolutions for efficient hierarchical feature extraction, while a compressed multi-scale feature module captures diverse polyp shapes and sizes. The decoder integrates high- and low-level features through a global semantic assembly strategy, enabling precise segmentation of irregular boundaries. UltraLightCPS achieves a Dice score of 92.58% on the CVC-ClinicDB dataset, requiring only 0.08 GFlops and delivering an inference speed of 113.73 frames per second. This positions UltraLightCPS as an efficient solution for real-time, edge-based clinical deployment, establishing a new benchmark in lightweight and accurate polyp segmentation for colorectal cancer screening.}
}
```
