---
title: "AATT+: Effectively manifesting concurrency bugs in Android apps"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yanyan Jiang
- Chang Xu
- Qiwei Li
- Tianxiao Gu
- Jun Ma
- Xiaoxing Ma
- Jian Lu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2018-10-01T00:00:00Z"
doi: "10.1016/j.scico.2018.03.008"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Science of Computer Programming*
publication_short: In *SCP*

abstract: Smartphones are indispensable in people's daily activities, and smartphone apps tend to be increasingly concurrent due to the wide use of multi-core devices and technologies. Due to this tendency, developers are increasingly unable to tackle the complexity of concurrent apps and to avoid subtle concurrency bugs. To better address this issue, we propose a novel approach to detecting concurrency bugs in Android apps based on the fact that one can generate simultaneous input events and their schedules for an app, which would easily trigger concurrency bugs in an app. We conduct systematic state space exploration to find potentially conflicting resource accesses in an Android app. The app is then automatically pressure-tested by guided event and schedule generation. We implemented our prototype tool named AATT+ and evaluated it with two sets of real-world Android apps. Benchmarking using 15 Android apps with previously known concurrency bugs, AATT+ and existing concurrency-unaware techniques detected 10 and 1 bugs, respectively. Evaluated with another set of 17 popular Android apps, AATT+ detected 11 concurrency bugs and 7 of them were previously unknown, achieving an over 80% higher detection rate than existing concurrency-unaware techniques.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
# - name: Custom Link
#   url: http://example.org

url_pdf: AATT+.pdf
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
- AATT+

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

