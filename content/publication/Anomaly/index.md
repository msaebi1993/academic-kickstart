---
title: "Efficient modeling of higher-order dependencies in networks: from algorithm to application for anomaly detection"
authors:
- admin
- Jian Xu
- Bruno Ribeiro
- Lance M. Kaplan
- Nitesh V. Chawla

date: "2020-06-09T00:00:00Z"
doi: "10.1140/epjds/s13688-020-00233-y"

# Schedule page publish date (NOT publication's date).

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Complex systems, represented as dynamic networks, comprise of components that influence each other via direct and/or indirect interactions. Recent research has shown the importance of using Higher-Order Networks (HONs) for modeling and analyzing such complex systems, as the typical Markovian assumption in developing the First Order Network (FON) can be limiting. This higher-order network representation not only creates a more accurate representation of the underlying complex system, but also leads to more accurate network analysis. In this paper, we first present a scalable and accurate model, BuildHON+, for higher-order network representation of data derived from a complex system with various orders of dependencies. Then, we show that this higher-order network representation modeled by BuildHON+ is significantly more accurate in identifying anomalies than FON, demonstrating a need for the higher-order network representation and modeling of complex systems for deriving meaningful conclusions.


# A major branch of anomaly detection methods relies on dynamic networks; raw sequence data is first converted to a series of networks, then critical change points are identified in the evolving network structure. However, existing approaches use first-order networks (FONs) to represent the underlying raw data, which may lose important higher-order sequence patterns, making higher-order anomalies undetectable in subsequent analysis. We present a novel higher-order anomaly detection method that is both parameter-free and scalable, building on an improved higher-order network (HON) construction algorithm. We show the proposed higher-order anomaly detection algorithm is effective in discovering variable orders of anomalies. Our data includes a synthetic 11 billion web clickstreams and a real-world taxi trajectory data.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. #Duis posuere tellus ac convallis placerat. Proin tincidunt magna #sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
#- name: Custom Link
#  url: ""
url_pdf: https://link.springer.com/content/pdf/10.1140/epjds/s13688-020-00233-y
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
# #url_slides: ''
#url_source: '#'
#url_video: '#'

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
- content/project/Anomaly/index.md

---

