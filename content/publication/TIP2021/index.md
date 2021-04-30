---
title: "Adaptive Streaming of 360 Videos with Perfect, Imperfect, and Unknown FoV Viewing Probabilities in Wireless Networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Ying Cui
- Zhi Liu
- Yunfei Zhang
- Sheng Yang

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Trans. Image Process.*
publication_short: In *IEEE Trans. Image Process. **(TIP)***

abstract: This paper investigates adaptive streaming of one or multiple tiled 360 videos from a multi-antenna base station (BS) to one or multiple single-antenna users, respectively, in a multi-carrier wireless system. We aim to maximize the video quality while keeping rebuffering time small via encoding rate adaptation at each group of pictures (GOP) and transmission adaptation at each (transmission) slot. To capture the impact of field-of-view (FoV) prediction, we consider three cases of FoV viewing probability distributions, i.e., perfect, imperfect, and unknown FoV viewing probability distributions, and use the average total utility, worst average total utility, and worst total utility as the respective performance metrics. In the single-user scenario, we optimize the encoding rates of the tiles, encoding rates of the FoVs, and transmission beamforming vectors for all subcarriers to maximize the total utility in each case. In the multi-user scenario, we adopt rate splitting with successive decoding and optimize the encoding rates of the tiles, encoding rates of the FoVs, rates of the common and private messages, and transmission beamforming vectors for all subcarriers to maximize the total utility in each case. Then, we separate the challenging optimization problem into multiple tractable problems in each scenario. In the single-user scenario, we obtain a globally optimal solution of each problem using transformation techniques and the Karush-Kuhn-Tucker (KKT) conditions. In the multi-user scenario, we obtain a KKT point of each problem using the concave-convex procedure (CCCP). Finally, numerical results demonstrate that the proposed solutions achieve notable gains over existing schemes in all three cases. To the best of our knowledge, this is the first work revealing the impact of FoV prediction on the performance of adaptive streaming of tiled 360 videos.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

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
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---



