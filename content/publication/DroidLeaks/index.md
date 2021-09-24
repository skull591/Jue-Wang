---
title: "DROIDLEAKS: a comprehensive database of resource leaks in Android apps"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yepang Liu
- admin
- Lili Wei
- Chang Xu
- Shing-Chi Cheung
- Tianyong Wu
- Jun Yan
- Jian Zhang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2019-5-16T00:00:00Z"
doi: "10.1007/s10664-019-09715-8"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-5-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Empirical Software Engineering*
publication_short: In *EMSE*

abstract: Resource leaks in Android apps are pervasive. They can cause serious performance degradation and system crashes. In recent years, many resource leak detection techniques have been proposed to help Android developers correctly manage system resources. Yet, there exist no common databases of real-world bugs for effectively comparing such techniques to understand their strengths and limitations. This paper describes our effort towards constructing such a bug database named DROIDLEAKS. To extract real resource leak bugs, we mined 124,215 code revisions of 34 popular open-source Android apps. After automated filtering and manual validation, we successfully found 292 fixed resource leak bugs, which cover a diverse set of resource classes, from 32 analyzed apps. To understand these bugs, we conducted an empirical study, which revealed the characteristics of resource leaks in Android apps and common patterns of resource management mistakes made by developers. To further demonstrate the usefulness of our work, we evaluated eight resource leak detectors from both academia and industry on DROIDLEAKS and performed a detailed analysis of their performance. We release DROIDLEAKS for public access to support future research. 


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
# - name: Custom Link
#   url: http://example.org

url_pdf: droidleaks.pdf
url_code: ''
url_dataset: https://zenodo.org/record/2589909#.YU3e6bhheUk
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
- DroidLeaks

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

