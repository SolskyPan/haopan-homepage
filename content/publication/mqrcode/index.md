---
title: "mQRCode: Secure QR Code Using Nonlinearity of Spatial Frequency in Light"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yi-Chao Chen
- Lanqing Yang 
- Guangtao Xue
- Chuang-Wen You
- Xiaoyu Ji

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2019-10-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 25th Annual International Conference On Mobile Computing And Networking*
publication_short: In *MobiCom 2019*

abstract: Quick response (QR) codes are becoming pervasive due to their rapid readability and the popularity of smartphones with built-in cameras. QR codes are also gaining importance in the retail sector as a convenient mobile payment method. However, researchers have concerns regarding the security of QR codes, which leave users susceptible to financial loss or private information leakage. In this study, we address this issue by developing a novel QR code (called mQRCode), which exploits patterns presenting a specific spatial frequency as a form of camouflage. When the targeted receiver holds a camera in a designated position (e.g., directly in front at a distance of 30 cm from the camouflaged QR code), the original QR code is revealed in form of a Moiré pattern. From any other position, only the camouflaged QR code can be seen. In experiments, the decryption rate of mQRCode was > 98.6% within 10.2 frames via a multi-frame decryption method. The decryption rate for cameras positioned 20° off axis or > 10cm away from the designated location dropped to 0%, indicating that mQRCode is robust against attacks.

# Summary. An optional shortened abstract.
summary: Moiré QR Code (mQRCode) achieves secure and robust QR code communication and is a software-based solution which requires no additional hardware or communication channels. It exploits nonlinearities in the spatial frequency of light rays to camouflage QR codes from the communication channel, i.e., the camera-screen channel.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3300061.3345428'
url_code: 'https://github.com/SolskyPan/mQRCode'
url_dataset: ''
url_poster: 'https://dl.acm.org/doi/abs/10.1145/3267305.3267626'
url_project: ''
url_slides: 'https://www.cs.sjtu.edu.cn/~yichao/pmwiki/assets/publications/mobicom19_pan.pptx'
url_source: ''
url_video: 'https://www.youtube.com/watch?v=gGQ-Bm64Pq8'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'mQRCode Application Scenarios'
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

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
