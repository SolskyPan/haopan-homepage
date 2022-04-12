---
title: "MagneComm: Magnetometer-based Near-Field Communication"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yi-Chao Chen
- Guangtao Xu
- Xiaoyu Ji

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2017-10-16T00:00:00Z"
doi: "https://doi.org/.1145/3117811.3117824"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-10-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 23th Annual International Conference On Mobile Computing And Networking*
publication_short: In *MobiCom 2017*

abstract: Near-field communication (NFC) plays a crucial role in the operation of mobile devices to enhance applications such as payment, social networks, private communication, gaming, and etc. Despite of the convenience, existing NFC standards like ISO-13157 require additional hardware (e.g., loop antenna and dedicated chip) and thereby hindering their wide-scale applications. In this work, we seek to propose a novel near-field communication protocol, MagneComm, which utilizes Magnetic Induction (MI) signals emitted from CPUs and captured by magnetometers on mobile devices for communication. Since CPUs and magnetometers are readily available components in mobile devices, MagneComm eliminates the requirement for special hardware and complements existing near-field communication protocols by providing additional bandwidth. We systematically analyze the characteristics of magnetic signals of CPUs and facilitate MagneComm with one-way communication, full-duplex communication, and multi-transmitter schemes in accordance with the hardware availability on devices. We prototype MagneComm on both laptops and smartphones. Extensive evaluation results show that MagneComm achieves up to 110 bps within 10 cm.


# Summary. An optional shortened abstract.
summary: MagnComm is a novel approach for near-field communication, which eliminates the need for dedicated hardware by embedding data stream into the MI signals of a CPU without affecting the normal function of the device.

tags: [Near-filed communication]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
