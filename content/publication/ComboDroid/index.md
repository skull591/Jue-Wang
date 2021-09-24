---
title: "ComboDroid: generating high-quality test inputs for Android apps via use case combinations"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yanyan Jiang
- Chang Xu
- Chun Cao
- Xiaoxing Ma
- Jian Lu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-06-27T00:00:00Z"
doi: "10.1145/3377811.3380382"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *the ACM/IEEE 42nd International Conference on Software Engineering*
publication_short: In *ICSE 2020*

abstract: |
Android apps demand high-quality test inputs, whose generation remains an open challenge. Existing techniques fall short on exploring complex app functionalities reachable only by a long, meaningful, and effective test input. Observing that such test inputs can usually be decomposed into relatively independent short use cases, this paper presents ComboDroid, a fundamentally different Android app testing framework. ComboDroid obtains use cases for manifesting a specific app functionality (either manually provided or automatically extracted), and systematically enumerates the combinations of use cases, yielding high-quality test inputs. 
The evaluation results of ComboDroid on real-world apps are encouraging. Our fully automatic variant outperformed the best existing technique APE by covering 4.6% more code (APE only outperformed Monkey by 2.1%), and revealed four previously unknown bugs in extensively tested subjects. Our semi-automatic variant boosts the manual use cases obtained with little manual labor, achieving a comparable coverage (only 3.2% less) with a white-box human testing expert.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
- ComboDroid

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
