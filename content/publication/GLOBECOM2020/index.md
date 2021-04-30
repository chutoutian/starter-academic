---
title: "Optimal Streaming of 360 VR Videos with Perfect, Imperfect and Unknown FoV Viewing Probabilities"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Ying Cui
- Chengjun Guo
- Zhi Liu
- Sheng Yang

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-12-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE GLOBECOM 2020*
publication_short: In *IEEE Global Communications Conference **(GLOBECOM)***

abstract: In this paper, we investigate wireless streaming of multi-quality tiled 360 virtual reality (VR) videos from a multi-antenna server to multiple single-antenna users in a multicarrier system. To capture the impact of field-of-view (FoV) prediction, we consider three cases of FoV viewing probability distributions, i.e., perfect, imperfect and unknown FoV viewing probability distributions, and use the average total utility, worst average total utility and worst total utility as the respective performance metrics. We adopt rate splitting with successive decoding for efficient transmission of multiple sets of tiles of different 360 VR videos to their requesting users. In each case, we optimize the encoding rates of the tiles, minimum encoding rates of the FoVs, rates of the common and private messages and transmission beamforming vectors to maximize the total utility. The problems in the three cases are all challenging nonconvex optimization problems. We successfully transform the problem in each case into a difference of convex (DC) programming problem with a differentiable objective function, and obtain a suboptimal solution using concave-convex procedure (CCCP). Finally, numerical results demonstrate the proposed solutions achieve notable gains over existing schemes in all three cases. To the best of our knowledge, this is the first work revealing the impact of FoV prediction and its accuracy on the performance of streaming of multi-quality tiled 360 VR videos.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'GLOBECOM2020.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'GLOBECOM2020_slides.pdf'
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



