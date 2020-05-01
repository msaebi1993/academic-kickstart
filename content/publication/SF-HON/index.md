---
title: "Detecting Anomalies in Sequential Data with Higher-order Networks"
authors:
- admin
date: "2019-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: A major branch of anomaly detection methods relies on dynamic networks; raw sequence data is first converted to a series of networks, then critical change points are identified in the evolving network structure. However, existing approaches use first-order networks (FONs) to represent the underlying raw data, which may lose important higher-order sequence patterns, making higher-order anomalies undetectable in subsequent analysis. We present a novel higher-order anomaly detection method that is both parameter-free and scalable, building on an improved higher-order network (HON) construction algorithm. We show the proposed higher-order anomaly detection algorithm is effective in discovering variable orders of anomalies. Our data includes a synthetic 11 billion web clickstreams and a real-world taxi trajectory data.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. #Duis posuere tellus ac convallis placerat. Proin tincidunt magna #sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
- name: Custom Link
  url: ""
url_pdf: https://arxiv.org/pdf/1712.09658.pdf
url_code: '#'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
