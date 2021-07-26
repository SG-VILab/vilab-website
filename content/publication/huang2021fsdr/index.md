---
title: "FSDR: Frequency Space Domain Randomization for Domain Generalization"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jiaxing Huang
- Dayan Guan
- Aoran Xiao
- Shijian Lu

date: "2021-06-01T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition* (**CVPR**), 2021
publication_short: In *Conference on Computer Vision and Pattern Recognition* (**CVPR**), 2021

abstract: Domain generalization aims to learn a generalizable model from a known source domain for various unknown target domains. It has been studied widely by domain randomization that transfers source images to different styles in spatial space for learning domain-agnostic features. However, most existing randomization uses GANs that often lack of controls and even alter semantic structures of images undesirably. Inspired by the idea of JPEG that converts spatial images into multiple frequency components (FCs), we propose Frequency Space Domain Randomization (FSDR) that randomizes images in frequency space by keeping domain-invariant FCs (DIFs) and randomizing domain-variant FCs (DVFs) only. FSDR has two unique features':' 1) it decomposes images into DIFs and DVFs which allows explicit access and manipulation of them and more controllable randomization; 2) it has minimal effects on semantic structures of images and domain-invariant features. We examined domain variance and invariance property of FCs statistically and designed a network that can identify and fuse DIFs and DVFs dynamically through iterative learning. Extensive experiments over multiple domain generalizable segmentation tasks show that FSDR achieves superior segmentation and its performance is even on par with domain adaptation methods that access target data in training.

# Display this page in the Featured widget?
featured: false

url_pdf: 'https://arxiv.org/pdf/2103.02370.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
