---
title:          MergeUp-augmented Semi-Weakly Supervised Learning for WSI Classification
date:           2024-08-23 00:01:00 +0800
selected:       true
pub:            "Arxiv"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-custom badge-success">Spotlight</span>'
pub_last:       ' <span class="badge badge-pill badge-custom badge-dark">Conference</span>'
pub_date:       "2024"

abstract: >-
  Recent progress in computational pathology and AI has enhanced WSI classification. However, the high resolution of WSIs and limited manual annotations pose challenges. MIL is a promising weakly supervised learning method for WSI classification. Research shows that pseudo bag augmentation can improve model performance by encouraging diverse data learning. Yet, directly using parent labels can introduce noise through mislabeling. To address this, we introduce SWS-MIL, which uses adaptive pseudo bag augmentation (AdaPse) to label data based on a threshold strategy. Additionally, we employ a "student-teacher" pattern with MergeUp, a feature augmentation technique that merges low-priority bags to enhance inter-category information and data diversity. Experiments on CAMELYON-16, BRACS, and TCGA-LUNG datasets demonstrate that our method outperforms current state-of-the-art approaches, confirming its effectiveness in WSI classification.
  
cover:          assets/images/covers/SWS_MIL.png
authors:
  - Mingxi Ouyang*
  - Yuqiu Fu*
  - Renao Yan*
  - ShanShan Shi
  - Xitong Ling
  - Lianghui Zhu†
  - Yonghong He†
  - Tian Guan†
links:
  Paper: https://arxiv.org/pdf/2408.12825

---
