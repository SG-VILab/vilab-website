---
title: "Brain MRI super-resolution using coupled-projection residual network"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Chun-Mei Feng
- Kai Wang
- Shijian Lu
- Yong Xu
- Xuelong Li

date: "2021-01-01T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Neurocomputing*, 2021
publication_short: In *Neurocomputing*, 2021

abstract: Magnetic Resonance Imaging (MRI) has been widely used in clinical application and pathology research to help doctors provide better diagnoses. However, accurate diagnosis by MRI remains a great challenge, as images obtained via current MRI techniques usually have low resolutions. Improving MRI image quality and resolution has thus become a critically important task. This paper presents an innovative Coupled-Projection Residual Network (CPRN) for MRI super-resolution. CPRN consists of two complementary sub-networks':' a shallow network and a deep one, which maintain content consistency while learning high frequency differences between low-resolution and high-resolution images. The shallow sub-network employs coupled-projection to better retain the MR image details, where a novel feedback mechanism is introduced to guide the reconstruction of high-resolution images. The deep sub-network learns from the residuals of the high-frequency image information, where multiple residual blocks are cascaded to magnify the MR images at the last network layer. Finally, the features from the shallow and deep sub-networks are fused for the reconstruction of high-resolution MR images. For effective feature fusion between the deep and shallow sub-networks, a step-wise connection (CPRN_S) is designed, inspired by the human cognitive process (from simple to complex). Experiments over three public MRI datasets show that our proposed CPRN achieves superior MRI super-resolution performance compared with the state-of-the-art.

# Display this page in the Featured widget?
featured: false

url_pdf: 'https://www.sciencedirect.com/science/article/abs/pii/S0925231221002502'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
