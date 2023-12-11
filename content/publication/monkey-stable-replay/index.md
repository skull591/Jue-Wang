---
title: "Understanding the Reproducibility Issues of Monkey for GUI Testing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Huiyu Liu
- Qichao Kong
- admin
- Ting Su
- Haiying Sun

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-11-1T00:00:00Z"
doi: "10.1145/3540250.3549170"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The Symposium on Dependable Software Engineering Theories, Tools and Applications*
publication_short: In *SETTA 2023*

abstract: Automated GUI testing is an essential activity in developing Android apps. Monkey is a widely used representative automated input generation (AIG) tool to efficiently and effectively detect crash bugs in Android apps. However, it faces challenges in reproducing the crash bugs it detects. To deeply understand the symptoms and root causes of these challenges, we conducted a comprehensive study on the reproducibility issues of Monkey with Android apps. We focused on Monkey’s capability to reproduce crash bugs using its built-in replay functionality and explored the root causes of its failures. Specifically, we selected six popular open-source apps and conducted automated instrumentation on them to monitor the invocations of event handlers within the apps. Subsequently, we performed GUI testing with Monkey on these instrumented apps for 6,000 test cases and collected 56 unique crash bugs. For each bug, we replayed it 200 times using Monkey’s replay function and calculated the success rate. Through manual analysis of screen recording files, log files of event handlers, and the source code of the apps, we pinpointed five root causes contributing to Monkey’s reproducibility issues: Injection Failure, Event Ambiguity, Data Loading, Widget Loading, and Dynamic Content. Our research showed that only 36.6% of the replays successfully reproduced the crash bugs, shedding light on Monkey’s limitations in consistently reproducing detected crash bugs. Additionally, we delved deep into the unsuccessfully reproduced replays to discern the root causes behind the reproducibility issues and offered insights for developing future AIG tool

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://tingsu.github.io/files/SETTA_2023.pdf
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

