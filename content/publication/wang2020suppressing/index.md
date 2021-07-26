---
title: "Suppressing Uncertainties for Large-Scale Facial Expression Recognition"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Kai Wang
- Xiaojiang Peng
- Jianfei Yang
- Shijian Lu
- Yu Qiao


date: "2020-06-01T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition* (**CVPR**), 2020
publication_short: In *Conference on Computer Vision and Pattern Recognition* (**CVPR**), 2020

abstract: Annotating a qualitative large-scale facial expression dataset is extremely difficult due to the uncertainties caused by ambiguous facial expressions, low-quality facial images, and the subjectiveness of annotators. These uncertainties lead to a key challenge of large-scale Facial Expression Recognition (FER) in deep learning era. To address this problem, this paper proposes a simple yet efficient Self-Cure Network (SCN) which suppresses the uncertainties efficiently and prevents deep networks from over-fitting uncertain facial images. Specifically, SCN suppresses the uncertainty from two different aspects':' 1) a self-attention mechanism over mini-batch to weight each training sample with a ranking regularization, and 2) a careful relabeling mechanism to modify the labels of these samples in the lowest-ranked group. Experiments on synthetic FER datasets and our collected WebEmotion dataset validate the effectiveness of our method. Results on public benchmarks demonstrate that our SCN outperforms current state-of-the-art methods with \textbf{88.14}\% on RAF-DB, \textbf{60.23}\% on AffectNet, and \textbf{89.35}\% on FERPlus.


# Display this page in the Featured widget?
featured: false

url_pdf: 'https://arxiv.org/pdf/2002.10392.pdf'
url_code: 'https://github.com/kaiwang960112/Self-Cure-Network'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
