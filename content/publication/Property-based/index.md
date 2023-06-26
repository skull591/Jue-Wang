---
title: "Property-based Fuzzing for Finding Data Manipulation Errors in Android Apps"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jingling Sun
- Ting Su
- Jiayi Jiang
- admin
- Geguang Pu
- Zhendong Su

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-6-25T00:00:00Z"
doi: "10.1145/3540250.3549170"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-6-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 30th ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering*
publication_short: In *ESEC/FSE 2022*

abstract: >
  Non-crashing functional bugs of Android apps can seriously affect user experience. Often buried in rare program paths, such bugs are difficult to detect but lead to severe consequences. Unfortunately, very few automatic functional bug oracles for Android apps exist, and they are all specific to limited types of bugs. In this paper, we introduce a novel technique named deep-state differential analysis, which brings the classical “bugs as deviant behaviors”oracle to Android apps as a generic automatic test oracle. Our oracle utilizes the observations on the execution of automatically generated test inputs that (1) there can be a large number of traces reaching internal app states with similar GUI layouts, and only a small portion of them would reach an erroneous app state, and (2) when performing the same sequence of actions on similar GUI layouts, the outcomes will be limited. Therefore, for each set of test inputs terminating at similar GUI layouts, we manifest comparable app behaviors by appending the same events to these inputs, cluster the manifested behaviors, and identify minorities as possible anomalies. We also calibrate the distribution of these test inputs by a novel input calibration procedure, to ensure the distribution of these test inputs is balanced with rare bug occurrences.

  We implemented the deep-state differential analysis algorithm as an exploratory prototype Odin and evaluated it against 17 popular real-world Android apps. Odin successfully identified 28 noncrashing functional bugs (five of which were previously unknown) of various root causes with reasonable precision. Detailed comparisons and analyses show that a large fraction (11/28) of these bugs cannot be detected by state-of-the-art techniques.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://cs.nju.edu.cn/changxu/1_publications/22/ESECFSE22_01.pdf
url_code: 'https://automatedoracleforandroid.github.io/Odin/'
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
- Odin

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
