---
title: "Fully Automated Functional Fuzzing of Android Apps for
Detecting Non-Crashing Logic Bugs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Ting Su
- Yichen Yan
- admin
- Jingling Sun
- Yiheng Xiong
- Geguang Pu
- Ke Wang
- Zhendong Su

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-10-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ACM SIGPLAN International Conference on Object-Oriented Programming, Systems, Languages, and Applications*
publication_short: In *SPLASH/OOPSLA 2021*

abstract: Android apps are GUI-based event-driven software and have become ubiquitous in recent years. Obviously, functional correctness is critical for an app’s success. However, in addition to crash bugs, non-crashing functional bugs (in short as “non-crashing bugs” in this work) like inadvertent function failures, silent user data lost and incorrect display information are prevalent, even in popular, well-tested apps. These non-crashing functional bugs are usually caused by program logic errors and manifest themselves on the graphic user interfaces (GUIs). In practice, such bugs pose significant challenges in effectively detecting them because (1) current practices heavily rely on expensive, small-scale manual validation (the lack of automation); and (2) modern fully automated testing has been limited to crash bugs (the lack of test oracles). This paper fills this gap by introducing independent view fuzzing, a novel, fully automated approach for detecting non-crashing functional bugs in Android apps. Inspired by metamorphic testing, our key insight is to leverage the commonly-held independent view property of Android apps to manufacture property-preserving mutant tests from a set of seed tests that validate certain app properties. The mutated tests help exercise the tested apps under additional, adverse conditions. Any property violations indicate likely functional bugs for further manual confirmation. We have realized our approach as an automated, end-to-end functional fuzzing tool, Genie. Given an app, (1) Genie automatically detects non-crashing bugs without requiring human-provided tests and oracles (thus fully automated); and (2) the detected non-crashing bugs are diverse (thus general and not limited to specific functional properties), which set Genie apart from prior work. We have evaluated Genie on 12 real-world Android apps and successfully uncovered 34 previously unknown non-crashing bugs in their latest releases — all have been confirmed, and 22 have already been fixed. Most of the detected bugs are nontrivial and have escaped developer (and user) testing for at least one year and affected many app releases, thus clearly demonstrating Genie’s effectiveness. According to our analysis, Genie achieves a reasonable true positive rate of 40.9%, while these 34 non-crashing bugs could not be detected by prior fully automated GUI testing tools (as our evaluation confirms). Thus, our work complements and enhances existing manual testing and fully automated testing for crash bugs


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
# - name: Custom Link
#   url: http://example.org

url_pdf: Genie.pdf
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
- Genie

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

