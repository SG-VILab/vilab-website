---
title: "S-CNN: Subcategory-Aware Convolutional Networks for Object Detection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Tao Chen
- Shijian Lu
- Jiayuan Fan

date: "2018-10-01T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Pattern Analysis and Machine Intelligence* (**TPAMI**), 2018
publication_short: In *IEEE Transactions on Pattern Analysis and Machine Intelligence* (**TPAMI**), 2018

abstract: The marriage between the deep convolutional neural network (CNN) and region proposals has made breakthroughs for object detection in recent years. While the discriminative object features are learned via a deep CNN for classification, the large intra-class variation and deformation still limit the performance of the CNN based object detection. We propose a subcategory-aware CNN (S-CNN) to solve the object intra-class variation problem. In the proposed technique, the training samples are first grouped into multiple subcategories automatically through a novel instance sharing maximum margin clustering process. A multi-component Aggregated Channel Feature (ACF) detector is then trained to produce more latent training samples, where each ACF component corresponds to one clustered subcategory. The produced latent samples together with their subcategory labels are further fed into a CNN classifier to filter out false proposals for object detection. An iterative learning algorithm is designed for the joint optimization of image subcategorization, multi-component ACF detector, and subcategory-aware CNN classifier. Experiments on INRIA Person dataset, Pascal VOC 2007 dataset and MS COCO dataset show that the proposed technique clearly outperforms the state-of-the-art methods for generic object detection.




# Display this page in the Featured widget?
featured: false

url_pdf: 'https://ieeexplore.ieee.org/document/8051100'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
