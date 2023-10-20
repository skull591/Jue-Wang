---
title: "Property-based Fuzzing for Finding Data Manipulation Errors in Android Apps"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jingling Sun
- Ting Su
- Jiaji Jiang
- admin
- Geguang Pu
- Zhendong Su

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2019-10-16T00:00:00Z"
doi: "10.1360/N112019-00003"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering*
publication_short: In *FSE 2023*

abstract: >
  Like many software applications, data manipulation functionalities (DMFs) are prevalent in Android apps, which perform the common CRUD operations (create, read, update, delete) to handle app-specific data. Thus, ensuring the correctness of these DMFs is fundamentally important for many core app functionalities. However, the bugs related to DMFs (named as data manipulation errors, DMEs), especially those non-crashing logic ones, are prevalent but difficult to find. To this end, inspired by property-based testing, we introduce a property-based fuzzing approach to effectively finding DMEs in Android apps. Our key idea is that, given some type of app data of interest, we randomly interleave its relevant DMFs and other possible events to explore diverse app states for thorough validation. Specifically, our approach characterizes DMFs in (data) model-based properties and leverage the consistency between the data model and the UI layouts as the handler to do property checking. The properties of DMFs are specified by human according to specific app features. To support the application of our approach, we implemented an automated GUI testing tool, PBFDroid. We evaluated PBFDroid on 20 real-world Android apps, and successfully found 30 unique and previously unknown bugs in 18 apps. Out of the 30 bugs, 29 of which are DMEs (22 are non-crashing logic bugs, and 7 are crash ones). To date, 19 have been confirmed and 9 have already been fixed. Many of these bugs are non-trivial and lead to different types of app failures. Our further evaluation confirms that none of the 22 non-crashing DMEs can be found by the state-of-the-art techniques. In addition, a user study shows that the manual cost of specifying the DMF properties with the assistance of our tool is acceptable. Overall, given accurate DMF properties, our approach can automatically find DMEs without any false positives.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://tingsu.github.io/files/fse23-PBFDroid.pdf
url_code: 'https://github.com/property-based-fuzzing/home'
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
- property

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

