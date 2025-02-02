---
# Documentation: https://hugoblox.com/docs/managing-content/

title: "AI Safety"
summary: "A 3 months group project consisting of an otherview on robustness and explainability of Machine Learning methods with an accent on adversarial attacks and defenses."
authors: [Baptiste Combelles, Clément Contet, Guillaume Coulaud, admin, Thibault Mousset, Guillaume Dupont, Aurélie Hurault, Philippe Quéinnec]
tags: [research, school]
categories: [research, school project]
date: 2023-03-16T22:30:20+01:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Colab Notebook
  url: https://colab.research.google.com/drive/16CuP9CqpOzVl9p1BPl5u-Bsi7XZj6Ek9?usp=sharing

url_code: "https://github.com/BaptisteCbl/surete-IA"
url_pdf: "project/ai-safety/ProjetLong.pdf"
url_slides: "project/ai-safety/PL_slides.pdf"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

## Summary
This Projet Long (litteraly Long Project) was a 3 months project in a group of 5 students on the topic of AI Safety, supervised by Guillaume Dupont, Aurélie Hurault and Philippe Quéinnec. This work consisted first in an extended litterature review and overview of the subject of robustness, verification and explainability of AI models such as Deep Neural Networks (DNNs) and Decision Trees (DTs). It then focused, with an approach more practical, on adversarial attacks and defenses of DNNs, formal verification of DNNs and DTs, and explainablity of more broad Machine Learning models.

## My Contribution
I contributed in this project to the setup and running of the adversarial attacks and training experiments, as well as a study on confidence learning, where the model outputs in addition a confidence bit in order to validate or invalidate its predicton, to measure the impact of an accurate confidence prediction on adversarial examples. I also carried out a test on Parametric Noise Injection, another robust training method, which did not perform better than adversarial training. My experiments code is primarily in the [`Colab Notebook`](https://colab.research.google.com/drive/16CuP9CqpOzVl9p1BPl5u-Bsi7XZj6Ek9?usp=sharing).