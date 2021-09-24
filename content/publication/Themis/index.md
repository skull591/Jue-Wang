---
title: "Benchmarking automated GUI testing for Android against real-world bugs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Ting Su
- admin
- Zhendong Su

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-8-20T00:00:00Z"
doi: "10.1145/3468264.3468620"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *the 29th ACM Joint Meeting on European Software Engineering Conference and Symposium on the Foundations of Software Engineering*
publication_short: In *ESEC/FSE 2021*

abstract: |
  For ensuring the reliability of Android apps, there has been tremendous, continuous progress on improving automated GUI testing in the past decade. Specifically, dozens of testing techniques and tools have been developed and demonstrated to be effective in detecting crash bugs and outperform their respective prior work in the number of detected crashes. However, an overarching question "How effectively and thoroughly can these tools find crash bugs in practice?" has not been well-explored, which requires a ground-truth benchmark with real-world bugs. Since prior studies focus on tool comparisons w.r.t. some selected apps, they cannot provide direct, in-depth answers to this question.

  To complement existing work and tackle the above question, this paper offers the first ground-truth empirical evaluation of automated GUI testing for Android. To this end, we devote substantial manual effort to set up the Themis benchmark set, including (1) a carefully constructed dataset with 52 real, reproducible crash bugs (taking two person-months for its collection and validation), and (2) a unified, extensible infrastructure with six recent state-of-the-art testing tools. The whole evaluation has taken over 10,920 CPU hours. We find a considerable gap in these tools finding the collected real bugs --- 18 bugs cannot be detected by any tool. Our systematic analysis further identifies five major common challenges that these tools face, and reveals additional findings such as factors affecting these tools in bug finding and opportunities for tool improvements. Overall, this work offers new concrete insights, most of which are previously unknown/unstated and difficult to obtain. Our study presents a new, complementary perspective from prior studies to understand and analyze the effectiveness of existing testing tools, as well as a benchmark for future research on this topic. The Themis benchmark is publicly available at https://github.com/the-themis-benchmarks/home.


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
# - name: Custom Link
#   url: http://example.org

url_pdf: Themis.pdf
url_code: https://github.com/the-themis-benchmarks/home
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
- Themis

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

