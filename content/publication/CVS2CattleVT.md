+++ 
abstract = "Monitoring cow body weight is crucial to support farm management decisions due to its direct relationship with the growth, nutritional status, and health of dairy cows. Cow body weight is a repeated trait, however, the majority of previous body weight prediction research only used data collected at a single point in time. Furthermore, the utility of deep learning-based segmentation for body weight prediction using videos remains unanswered. Therefore, the objectives of this study were to predict cow body weight from repeatedly measured video data, to compare the performance of the thresholding and Mask R-CNN deep learning approaches, to evaluate the predictive ability of body weight regression models, and to promote open science in the animal science community by releasing the source code for video-based body weight prediction. An Intel RealSense D435 camera was installed on Virginia Tech dairy complex to collect top-view videos of 10 lactating Holstein cows twice a day for 28 days after milking sessions and 2 non-lactating, pregnant Jersey cows once a week upon calving. At the same time, the ground truth body weight records were collected using a walk-over weighing system. A total of 40,405 depth images and depth map files were obtained. Three approaches were investigated to segment the cow's body from the background, including single thresholding, adaptive thresholding, and Mask R-CNN. Four image-derived biometric features, such as dorsal length, abdominal width, height, and volume, were estimated from the segmented images and fitted using ordinary least squares, ridge regression, least absolute shrinkage and selection operator, and linear mixed models. Two cross-validation designs, forecasting and leave-three-cows-out, were used to evaluate prediction performance. The Pearson correlation between image-derived biometric features and scale-based body weight ranged from 0.74 to 0.95. On average, the Mask-RCNN approach combined with a linear mixed model resulted in the best prediction coefficient of determination and mean absolute percentage error of 0.98 and 2.03%, respectively, in the forecasting cross-validation. The Mask-RCNN approach was also the best in the leave-three-cows-out cross-validation, followed by adaptive and single thresholding. The prediction coefficients of determination and mean absolute percentage error of the Mask-RCNN coupled with the linear mixed model were 0.90 and 4.70%, respectively. Our results suggest that deep learning-based segmentation improves the prediction performance of cow body weight from longitudinal depth video data."
abstract_short = ""
authors = ["Ye Bi", "Leticia M.Campos", "Jin Wang", "__Haipeng Yu__", "Mark D.Hanigan", "and Gota Morota"]
date = "2023-12-01"
# image = ""
# image_preview = ""
math = true
publication = "Smart Agricultural Technology"
publication_short = "Smart Agricultural Technology"
publication_types = ["2"]
selected = false
title = "Depth video data-enabled predictions of longitudinal dairy cow body weight using thresholding and Mask R-CNN algorithms"
url_code = ""
url_dataset = ""
# url_pdf = "papers/"
url_project = ""
url_slides = ""
url_video = ""

[[url_custom]]
name = "DOI"
url = "https://doi.org/10.1016/j.atech.2023.100352"

# [[url_custom]]
# name = "PubMed"
# url = "https://www.ncbi.nlm.nih.gov/pubmed/30992319"
# 
# [[url_custom]]
# name = "EuropePMC"
# url = "http://europepmc.org/article/MED/30992319"

# [[url_custom]]
# name = "bioRxiv"
# url = "https://www.biorxiv.org/content/10.1101/2020.09.03.282335v2"
+++
