---
title: "NavyDroid: Detecting Energy Inefficiency Problems for Smartphone Applications"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yi Liu
- admin
- Chang Xu
- Xiaoxing Ma

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2017-09-23T00:00:00Z"
doi: "10.1145/3131704.3131705"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-09-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *the 9th Asia-Pacific Symposium on Internetware*
publication_short: In *Internetware 2017*

abstract: |
  Many smartphone applications suffer from energy inefficiency problems, but locating these problems is quite difficult and labor-intensive. Automated tools for detecting energy inefficiency bugs have been shown to be effective. Existing approaches generally consist of two parts, namely the simulation part and the monitor part. The simulation part explores an application's state space guided by an application execution model, and the monitor part checks for occurrences of energy inefficiency patterns. However, existing approaches might miss energy inefficiency bugs due to their imprecise application execution models and oversimplified energy inefficiency diagnosis policies. In this paper, we proposed NavyDroid, an approach to diagnosing energy inefficiency problems more effectively. We summarized a comprehensive application execution model from Android specifications and expressed it as a state machine. By considering multiple patterns of wake lock misuses, our approach is able to detect more complex energy bugs caused by wake lock misuses. We implemented NavyDroidon top of Java Pathfinder (JPF) and applied it to real-world applications. We evaluated NavyDroid with 17 real-world Android applications, and NavyDroid located more energy inefficiency bugs in these applications than the existing work E-GreenDroid did. The results of our experiments demonstrate that our approach can effectively locate real energy inefficiency bugs in Android applications, suggesting its effectiveness.


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
# - name: Custom Link
#   url: http://example.org

url_pdf: navy.pdf
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
- NavyDroid-internetware

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

