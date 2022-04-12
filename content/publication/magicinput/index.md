---
title: "Magicinput: Training-free multi-lingual finger input system using data augmentation based on mnists"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yi-Chao Chen
- Qi Ye
- Guangtao Xue

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2021-05-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 20th International Conference on Information Processing in Sensor Networks*
publication_short: In *IPSN 2021*

abstract: Text input systems based on device-free finger tracking technologies have attracted considerable attention in the use scenarios of mobile and the Internet-of-Things (IoT) devices. Issues pertaining to 2D tracking have prompted interest in using 1D finger trajectories for the recognition of handwritten letters. Nonetheless, 1D tracking imposes two major challenges, (i) Trajectory information loss from 2D to 1D; and (ii) Inter-user diversity in writing traits. These challenges could possibly be overcome by collecting a large training dataset for every user; however, this would impose an unacceptable burden on users. This paper presents a text input system with multi-language support without training using acoustic-based 1D finger tracking technology. We developed a novel data augmentation scheme, in which the handwritten image dataset MNISTs are used to create artificial datasets (called TrackMNISTs). We compensate for the trajectory information loss of 1D by creating personal dataset (from TrackMNIST) to match the writing habits of individual users. The proposed data augmentation mechanism is also applicable to multilingual letter recognition. In experiments, MagicInput achieved outstanding classification accuracy on unseen users, 10 digits (98.3%), 26 uppercase/lowercase English letters (97.8%/95.3%), 49 Japanese characters (91.4%), and the 30 commonly used Chinese characters (93.8%).

# Summary. An optional shortened abstract.
summary: MagicInput is a training-free text input system that support multiple languages using acoustic-based 1D finger tracking technology.

tags: [Human-computer interaction]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3412382.3458261'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.cs.sjtu.edu.cn/~yichao/pmwiki/assets/publications/IPSN21_Pan.pptx'
url_source: ''
url_video: 'https://www.youtube.com/watch?v=bzh8fU9qYTU'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'MagicInput Teaser'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
