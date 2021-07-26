---
title: "YoTube: Searching Action Proposal via Recurrent and Static Regression Networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Hongyuan Zhu
- Romain Vial
- Shijian Lu
- Yonghong Tian
- Xianbin Cao


date: "2018-06-01T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Image Processing* (**TIP**), 2018
publication_short: In *IEEE Transactions on Image Processing* (**TIP**), 2018

abstract: In this paper, we propose YoTube-a novel deep learning framework for generating action proposals in untrimmed videos, where each action proposal corresponds to a spatial-temporal tube that potentially locates one human action. Most of the existing works generate proposals by clustering low-level features or linking image proposals, which ignore the interplay between long-term temporal context and short-term cues. Different from these works, our method considers the interplay by designing a new recurrent YoTube detector and static YoTube detector. The recurrent YoTube detector sequentially regresses candidate bounding boxes using Recurrent Neural Network learned long-term temporal contexts. The static YoTube detector produces bounding boxes using rich appearance cues in every single frame. To fully exploit the complementary appearance, motion, and temporal context, we train the recurrent and static detector using RGB (Color) and flow information. Moreover, we fuse the corresponding outputs of the detectors to produce accurate and robust proposal boxes and obtain the final action proposals by linking the proposal boxes using dynamic programming with a novel path trimming method. Benefiting from the pipeline of our method, the untrimmed video could be effectively and efficiently handled. Extensive experiments on the challenging UCF-101, UCF-Sports, and JHMDB datasets show superior performance of the proposed method compared with the state of the arts.



# Display this page in the Featured widget?
featured: false

url_pdf: 'https://ieeexplore.ieee.org/document/8291617'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
