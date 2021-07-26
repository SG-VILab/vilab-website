---
title: "Single-Image Dehazing via Compositional Adversarial Network"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Hongyuan Zhu
- Yi Cheng
- Xi Peng
- Joey Tianyi Zhou
- Zhao Kang
- Shijian Lu
- Zhiwen Fang
- Liyuan Li
- Joo-Hwee Lim

date: "2019-12-01T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Cybernetics* (**TCYB**), 2019
publication_short: In *IEEE Transactions on Cybernetics* (**TCYB**), 2019

abstract: Single-image dehazing has been an important topic given the commonly occurred image degradation caused by adverse atmosphere aerosols. The key to haze removal relies on an accurate estimation of global air-light and the transmission map. Most existing methods estimate these two parameters using separate pipelines which reduces the efficiency and accumulates errors, thus leading to a suboptimal approximation, hurting the model interpretability, and degrading the performance. To address these issues, this article introduces a novel generative adversarial network (GAN) for single-image dehazing. The network consists of a novel compositional generator and a novel deeply supervised discriminator. The compositional generator is a densely connected network, which combines fine-scale and coarse-scale information. Benefiting from the new generator, our method can directly learn the physical parameters from data and recover clean images from hazy ones in an end-to-end manner. The proposed discriminator is deeply supervised, which enforces that the output of the generator to look similar to the clean images from low-level details to high-level structures. To the best of our knowledge, this is the first end-to-end generative adversarial model for image dehazing, which simultaneously outputs clean images, transmission maps, and air-lights. Extensive experiments show that our method remarkably outperforms the state-of-the-art methods. Furthermore, to facilitate future research, we create the HazeCOCO dataset which is currently the largest dataset for single-image dehazing.


# Display this page in the Featured widget?
featured: false

url_pdf: 'https://ieeexplore.ieee.org/document/8946591'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
