---
title: "Sembug: Detecting Logic Bugs in Dbms Through Generating Semantic-Aware Non-Optimizing Query"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Shiyang Ye
- Chao Ni
- admin
- Qianqian Pang
- Xinrui Li
- Xiaodan Xu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2025-06-17T00:00:00Z"
doi: "10.1109/ICPC66645.2025.00021"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE/ACM 33rd International Conference on Program Comprehension*
publication_short: In *ICPC 2025*

abstract: "Logic bugs, which cause Database Management Systems (DBMSs) to return incorrect results, are challenging to detect due to the absence of explicit signs such as system crashes. The majority of these bugs originate from the query optimizer and are commonly referred to as optimization bugs. Many approaches have been proposed for detecting logic bugs, which can be divided into two groups. The first group aims to detect the optimization bugs but only focuses on those with incorrect results cardinality, neglecting to check semantic correctness and consequently limiting the detection of bugs in advanced DBMS features. For the second group, though it can verify the correctness of the results for both their cardinality and semantics, it is ineffective in handling optimization bugs, which restricts its practical usage effectiveness. In this paper, we propose Semantic-aware Non-Optimizing Query (SemBug), a novel approach for logic bug detection in DBMSs. SemBug focuses on optimization bugs by transforming the queries that can be highly optimized by DBMS into equivalent but less optimized ones. Additionally, SemBug integrates semantic analysis technology, enabling it to identify semantic logic bugs and support testing advanced DBMS features. Any discrepancy in cardinality or content between the original and transformed queries indicates a logic bug. To investigate the effectiveness of SemBug, we conduct a large-scale experiment on five widelyused DBMS systems (i.e., MySQL, TiDB, MariaDB, SQLite, and PostgreSQL) and compare it with three state-of-the-art (SOTA) approaches (i.e., Pinolo, TLP, and NoREC). The experimental results indicate that SemBug outperforms three SOTAs. Over 24 hours, SemBug found 34 unique logic bugs, which are 19, 14, and 13 more bugs than each of the three SOTAs, marking an improvement of 126%,70%, and 61 % respectively. As of the time of paper submission, SemBug has uncovered 37 unique logic bugs, of which 29 have been verified by developers, and 11 have been fixed. SemBug helps developers identify these bugs, providing insights into such inconsistencies and assisting in resolving them."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://ieeexplore.ieee.org/abstract/document/11025894/authors#authors
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
- monkey-stable-replay

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

