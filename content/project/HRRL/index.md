---
title: Relational Reasoning in Knowledge Graphs
# summary: Heterogeneous Relational Reasoning in Knowledge Graphs with Reinforcement Learning
summary: " "
tags:
- Reinforcement Learning, Knowledge Graphs, Relational Reasoning
date: "2020-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: Smart

# links:
# - icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: ""
# url_code: ""
url_pdf: "https://arxiv.org/pdf/2003.06050"
# url_slides: ""
url_video: "https://youtu.be/-hD-x8z3kbg"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Path-based relational reasoning over knowledge graphs has become increasingly popular due to a variety of downstream applications such as question answering in dialogue systems, fact prediction, and recommendation systems. 

In recent years, reinforcement learning (RL) based solutions have been demonstrated to be more interpretable and explainable than other deep learning models. However, the current solutions still struggle with performance issue due to incomplete state representation and large action space for the RL agent. We address these problems by introducing HRRL, a type-enhanced RL agent that utilizes the local heterogeneous neighborhood information for efficient path-based reasoning over knowledge graphs. Our solution improves the state representation using a graph neural network (GNN) for encoding the neighborhood information and utilizes entity type information for pruning the action space. Extensive experiments on real-world datasets show that our method outperforms state-of-the-art RL methods and discovers more novel paths during the training procedure, demonstrating the explorative power of our method.