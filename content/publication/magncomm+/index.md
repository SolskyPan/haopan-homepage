---
title: "MagneComm+: Near-Field Electromagnetic Induction Communication with Magnetometer"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Guangtao Xue
- admin
- Yi-Chao Chen
- Xiaoyu Ji
- Jiadi Yu

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2021-12-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Transactions on Mobile Computing*
publication_short: In *IEEE TMC*

abstract: Near-field communication (NFC) technology emerges as a vital role with appealing benefits for users to improve mobile device's functionality. Although today's most smartphones and smartwatches come with NFC support, other mobile devices (e.g., PC and laptops) and IoT devices that don't equip with dedicated radio modules cannot take advantage of wide-scale NFC capability. We design and develop MagneComm+, an NFC implementation scheme without dedicated hardware and propose a novel near-field communication protocol that is applicable to almost all mobile devices and IoT devices. The key idea is to utilize the electromagnetic induction (EMI) signal emitted from the computing devices (e.g., CPUs) and captured by magnetometers on mobile devices for communication. We tackle challenges in data encoding/decoding, preamble detection, retransmission and error correction, multi-transmitter, and full-duplex schemes, to efficiently generate and reliably receive EMI signal with the hardware available on devices. We prototype MagneComm+ on both between laptops and smartphones, as well as between two laptops with an external magnetometer. Extensive evaluation results show that our MagneComm+ supports around 10cm communication distance with average 110 bit per second (bps) data rate on the normal-speed mode, and maximum 17.28kbps on the full-speed mode.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9645063'
url_code: 'https://github.com/SolskyPan/MagneComm'
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
