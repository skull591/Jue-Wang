---
title: "ELEGANT: Towards Effective Location of Fragmentation-Induced Compatibility Issues for Android Apps"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Cong Li
- Chang Xu
- Lili Wei
- admin
- Jun Ma
- Jian Lu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2018-12-04T00:00:00Z"
doi: "https://doi.org/10.1109/APSEC.2018.00042"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-12-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *25th Asia-Pacific Software Engineering Conference (APSEC)*
publication_short: In *APSEC 2018*

abstract: Android fragmentation is a double-edged sword of the Android ecosystem. On the one hand, it promotes Android's prevalence. On the other hand, the numerous combinations of various system versions, customized features, system drivers, and device models make it infeasible, if not impossible, for developers to exhaustively test their apps for potential compatibility issues. Previous research has proposed promising techniques for detecting these issues. However, they suffer from severe false positive problems due to their lack of third-party library detection or imprecise program analysis. In this paper, we present ELEGANT, an automated tool to effectively detect and locate fragmentation-induced compatibility issues for Android apps. ELEGANT exploits whitelist-enhanced or obfuscation-insensitive techniques to detect and alleviate the impact of third-party libraries on the analysis precision, and uses a three-step static detection algorithm to increase the precision of its program analysis. We experimentally evaluated ELEGANT with 22 real-world popular Android apps. The experimental results confirmed ELEGANT's effectiveness on detecting and locating Android fragmentation-induced compatibility issues, as well as realizing an impressive reduction on false positives by around 70%.


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
# - name: Custom Link
#   url: http://example.org

url_pdf: APSEC18.pdf
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
- Elegant

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

