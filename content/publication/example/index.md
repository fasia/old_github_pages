---
title: "Vulnerability assessment of web services with model-based mutation testing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Dragos Truscan
- Juri Vain

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2018-07-20T00:00:00Z"
doi: "10.1109/QRS.2018.00043"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-07-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2018 IEEE International Conference on Software Quality, Reliability and Security*
publication_short: In *QRS*

abstract: We present a model-based mutation testing approach, for evaluating the authentication and authorization of web services in a multi-user context. Model of a web service and its security requirements are designed using UPPAAL Timed Automata. The model is mutated to create invalid behavior which is used for test generation to reveal faults in the system under test. The approach is supported by a model-based mutation testing tool, μUTA, that automatically generates mutants, selects a collection of suitable mutants for testing and generates test cases from them. We modify a previously defined mutation operator and introduce three new operators for additional mutants. We define criteria for the mutation-selection and demonstrate the approach on a blog web service. Results show that the approach can discover authorization faults that were not detected by traditional methods.

# Summary. An optional shortened abstract.
summary: ""

tags: [model-based Testing, mutation testing, web services]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/8424981'
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
  caption: 'MBMT'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Mega Modelling Project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: qrs
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
