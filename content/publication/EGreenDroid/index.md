---
title: "E-greenDroid: effective energy inefficiency analysis for android applications"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yepang Liu
- Chang Xu
- Xiaoxing Ma
- Jian Lu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2016-9-18T00:00:00Z"
doi: "10.1145/2993717.2993720"

# Schedule page publish date (NOT publication's date).
publishDate: "2016-9-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In * 8th Asia-Pacific Symposium on Internetware*
publication_short: In *Internetware 2016*

abstract: |
  Energy inefficiency of smartphone apps is one of the important non-functional issues. It is common, but difficult to diagnose, and often involves sensor usage. GreenDroid provides a novel approach to systematically diagnose energy inefficiency problems in smartphone apps running on Android platforms. It derives an application execution model (AEM) from Android framework and leverages it to realistically simulate an application's runtime behaviors. It also automatically analyzes an application's sensory data utilization, monitors sensor listener and wake lock usage, and reports actionable information to developers.

  However, GreenDroid has several limitations. First, other than Android 2.3, it does not support other newer versions of Android. Second, GreenDroid doesn't provide an actionable and reusable state machine based on AEM. Third, its implementation and report generation need optimization. This work focuses on extending GreenDroid's functionality of diagnosing energy inefficiency problems in Android apps. We re-implement GreenDroid on the newest version of Java Pathfinder(JPF), update and optimize the execution simulation process as well as library modeling. Besides, this work adds support to new Android features such as Fragment, and abstracts a separate and reusable state machine out of AEM. With our evaluation, we demonstrate that the extended GreenDroid (E-GreenDroid) can analyze those apps with new Android features while being the same effective as the original version.


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
# - name: Custom Link
#   url: http://example.org

url_pdf: EGreenDroid.pdf
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
- EGreenDroid

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
