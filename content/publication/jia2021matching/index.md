---
title: "Matching on Sets: Conquer Occluded Person Re-identification Without Alignment"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Mengxi Jia
- Xinhua Cheng
- Yunpeng Zhai
- Shijian Lu
- Siwei Ma
- Yonghong Tian
- Jian Zhang

date: "2021-01-01T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *AAAI Conference on Artificial Intelligence* (**AAAI**), 2021
publication_short: In *AAAI Conference on Artificial Intelligence* (**AAAI**), 2021

abstract: Occluded person re-identification (re-ID) is a challenging task as different human parts may become invisible in cluttered scenes, making it hard to match person images of different identities. Most existing methods address this challenge by aligning spatial features of body parts according to semantic information (e.g. human poses) or feature similarities but this approach is complicated and sensitive to noises. This paper presents Matching on Sets (MoS), a novel method that positions occluded person re-ID as a set matching task without requiring spatial alignment. MoS encodes a person image by a pattern set as represented by a `global vector’ with each element capturing one specific visual pattern, and it introduces Jaccard distance as a metric to compute the distance between pattern sets and measure image similarity. To enable Jaccard distance over continuous real numbers, we employ minimization and maximization to approximate the operations of intersection and union, respectively. In addition, we design a Jaccard triplet loss that enhances the pattern discrimination and allows to embed set matching into deep neural networks for end-to-end training. In the inference stage, we introduce a conflict penalty mechanism that detects mutually exclusive patterns in the pattern union of image pairs and decreases their similarities accordingly. Extensive experiments over three widely used datasets (Market1501, DukeMTMC and Occluded-DukeMTMC) show that MoS achieves superior re-ID performance. Additionally, it is tolerant of occlusions and outperforms the state-of-the-art by large margins for Occluded-DukeMTMC.

# Display this page in the Featured widget?
featured: false

url_pdf: 'https://ojs.aaai.org/index.php/AAAI/article/view/16260'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
