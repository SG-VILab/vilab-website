---
title: "Diverse Image Inpainting with Bidirectional and Autoregressive Transformers"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yingchen Yu
- Fangneng Zhan
- Rongliang Wu
- Jianxiong Pan
- Kaiwen Cui
- Shijian Lu
- Feiying Ma
- Xuansong Xie
- Chunyan Miao




date: "2021-07-01T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ACM International Conference on Multimedia* (**ACM MM**), 2021
publication_short: In *ACM International Conference on Multimedia* (**ACM MM**), 2021

abstract: Image inpainting is an underdetermined inverse problem, which naturally allows diverse contents to fill up the missing or corrupted regions realistically. Prevalent approaches using convolutional neural networks (CNNs) can synthesize visually pleasant contents, but CNNs suffer from limited perception fields for capturing global features. With image-level attention, transformers enable to model long-range dependencies and generate diverse contents with autoregressive modeling of pixel-sequence distributions. However, the unidirectional attention in autoregressive transformers is suboptimal as corrupted image regions may have arbitrary shapes with contexts from any direction. We propose BAT-Fill, an innovative image inpainting framework that introduces a novel bidirectional autoregressive transformer (BAT) for image inpainting. BAT utilizes the transformers to learn autoregressive distributions, which naturally allows the diverse generation of missing contents. In addition, it incorporates the masked language model like BERT, which enables bidirectionally modeling of contextual information of missing regions for better image completion. Extensive experiments over multiple datasets show that BAT-Fill achieves superior diversity and fidelity in image inpainting qualitatively and quantitatively.




# Display this page in the Featured widget?
featured: false

url_pdf: 'https://arxiv.org/abs/2104.12335'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
