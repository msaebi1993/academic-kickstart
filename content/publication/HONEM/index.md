---
title: "HONEM: Network Embedding Using Higher-Order Patterns in Sequential Data"
authors:
- admin
- Giovanni Luca Ciampaglia
- Lance M Kaplan
- Nitesh V Chawla 

date: "2019-08-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
#publication: "*Journal of Source Themes, 1*(1)"
#publication_short: ""

abstract: Representation learning offers a powerful alter- native to the oft painstaking process of manual feature engineering, and as a result, has enjoyed considerable success in recent years. This success is especially striking in the context of graph mining, since networks can take advantage of vast troves of sequential data to encode information about interactions between entities of interest. But how do we learn embeddings on networks that have higher-order and sequential dependen- cies? Existing network embedding methods naively assume the Markovian property (first-order dependency) for node interactions, which may not capture the time-dependent and longer-range underlying complex interactions of the raw data. To address the limitation of current methods, we propose a network embedding method for higher-order networks (HON). We demonstrate that the higher-order network embedding (HONEM) method is able to extract higher-order dependencies from HON to construct the higher-order neighborhood matrix of the network, while existing methods are not able to capture these higher-order dependencies. We show that our method outperforms other state-of-the-art methods in node classifica- tion, network reconstruction, link prediction, and visualization.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. #Duis posuere tellus ac convallis placerat. Proin tincidunt magna #sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/1908.05387.pdf
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# #url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- content/project/HONEM/index.md


---



