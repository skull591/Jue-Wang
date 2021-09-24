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
- Jian Lu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2018-05-01T00:00:00Z"
doi: "10.1007/s11432-017-9400-y"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Science China Information Science*
publication_short: In *SCIS*

abstract: |
  Energy inefficiency is an influential non-functional issue for smartphone applications, causing increased concerns from users. Locating these problems is labor-intensive, thus automated diagnosis tools are in demand. Some existing approaches detect energy inefficiency problems by exploring application states with the JPF framework, and get favorable results. However, the effects of these approaches are restricted because of their imprecise application execution models and incomplete energy inefficiency patterns. This paper introduces NavyDroid, an effective and efficient tool of energy inefficiency problem diagnosis for Android applications. We constructed a comprehensive application execution model in the form of a state machine, which accurately simulates the runtime behavior of Android applications. We designed a parallel algorithm to systematically explore an application’s state space. Our approach supports more energy inefficiency patterns, and is able to detect complicated wake lock misuses. We implemented our approach as a prototype tool and applied it to real-world applications. We evaluated NavyDroid with 19 real-world Android applications, and NavyDroid located more energy inefficiency bugs in these applications than the existing work E-GreenDroid did. Also, NavyDroid reduced the analysis time with its parallel state exploration algorithm. The experimental results demonstrated the effectiveness and efficiency of our approach for detecting energy inefficiency bugs in Android applications.


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
# - name: Custom Link
#   url: http://example.org

url_pdf: navydroid.pdf
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
- NavyDroid-SCIS

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

