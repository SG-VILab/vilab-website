---
title: "SS-HCNN:Semi-Supervised Hierarchical Convolutional Neural Network for Image Classification"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Tao Chen
- Shijian Lu
- Jiayuan Fan

date: "2019-05-01T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Image Processing* (**TIP**), 2019
publication_short: In *IEEE Transactions on Image Processing* (**TIP**), 2019

abstract: The availability of large-scale annotated data and the uneven separability of different data categories have become two major impediments of deep learning for image classification. In this paper, we present a semi-supervised hierarchical convolutional neural network (SS-HCNN) to address these two challenges. A large-scale unsupervised maximum margin clustering technique is designed, which splits images into a number of hierarchical clusters iteratively to learn cluster-level CNNs at parent nodes and category-level CNNs at leaf nodes. The splitting uses the similarity of CNN features to group visually similar images into the same cluster, which relieves the uneven data separability constraint. With the hierarchical cluster-level CNNs capturing certain high-level image category information, the category-level CNNs can be trained with a small amount of labeled images, and this relieves the data annotation constraint. A novel cluster splitting criterion is also designed, which automatically terminates the image clustering in the tree hierarchy. The proposed SS-HCNN has been evaluated on the CIFAR-100 and ImageNet classification datasets. The experiments show that the SS-HCNN trained using a portion of labeled training images can achieve comparable performance with other fully trained CNNs using all labeled images. Additionally, the SS-HCNN trained using all labeled images clearly outperforms other fully trained CNNs.


# Display this page in the Featured widget?
featured: false

url_pdf: 'https://ieeexplore.ieee.org/document/8576611'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
