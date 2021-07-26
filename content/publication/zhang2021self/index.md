---
title: "Self-Guided Adaptation: Progressive Representation Alignment for Domain Adaptive Object Detection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Zongxian Li
- Qixiang Ye
- Chong Zhang
- Jingjing Liu
- Shijian Lu
- Yonghong Tian

date: "2021-05-01T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Multimedia* (**TMM**), 2021
publication_short: In *IEEE Transactions on Multimedia* (**TMM**), 2021

abstract: Unsupervised domain adaptation (UDA) has achieved unprecedented success in improving the cross-domain robustness of object detection models. However, existing UDA methods largely ignore the instantaneous data distribution during model learning, which could deteriorate the feature representation given large domain shift. In this work, we propose a Self-Guided Adaptation (SGA) model, target at aligning feature representation and transferring object detection models across domains while considering the instantaneous alignment difficulty. The core of SGA is to calculate "hardness" factors for sample pairs indicating domain distance in a kernel space. With the hardness factor, the proposed SGA adaptively indicates the importance of samples and assigns them different constrains. Indicated by hardness factors, Self-Guided Progressive Sampling (SPS) is implemented in an "easy-to-hard" way during model adaptation. Using multi-stage convolutional features, SGA is further aggregated to fully align hierarchical representations of detection models. Extensive experiments on commonly used benchmarks show that SGA improves the state-of-the-art methods with significant margins, while demonstrating the effectiveness on large domain shift.



# Display this page in the Featured widget?
featured: false

url_pdf: 'https://arxiv.org/pdf/2003.08777.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
