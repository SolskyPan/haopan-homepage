---
title: "MagAttack: Guessing Application Launching and Operation via Smartphone"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yushi Cheng
- Xiaoyu Ji
- Wenyuan Xu
- admin
- Zhuangdi Zhu
- Chuang-Wen You
- Yi-Chao Chen
- Lili Qiu

# Author notes (optional)
date: "2019-07-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-07-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 14th ACM ASIA Conference on Computer and Communications Security*
publication_short: In *ACM ASIACCS*

abstract: Mobile devices have emerged as the most popular platforms to access information. However, they have also become a major concern of privacy violation and previous researches have demonstrated various approaches to infer user privacy based on mobile devices. In this paper, we study a new side channel of a laptop that could be harvested by a commercial-off-the-shelf (COTS) mobile device, eg, a smartphone. We propose MagAttack, which exploits the electromagnetic (EM) side channel of a laptop to infer user activities, i.e., application launching and application operation. The key insight of MagAttack is that applications are discrepant in essence due to the different compositions of instructions, which can be reflected on the CPU power consumption, and thus the corresponding EM emissions. MagAttack is challenging since that EM signals are noisy due to the dynamics of applications and the limited sampling rate of the built-in magnetometers in COTS mobile devices. We overcome these challenges and convert noisy coarse-grained EM signals to robust fine-grained features. We implement MagAttack on both an iOS and an Android smartphone without any hardware modification, and evaluate its performance with 13 popular applications and 50 top websites in China. The results demonstrate that MagAttack can recognize aforementioned 13 applications with an average accuracy of 98.6%, and figure out the visiting operation among 50 websites with an average accuracy of 84.7%.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3321705.3329817'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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
slides: ""
---

