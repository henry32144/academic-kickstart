---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Continuous Control"
summary: "Training an agent to maintain double-jointed arms' position."
authors: ["ChengHan Wu"]
tags: ["Reinforcement Learning"]
categories: ["Course Projects"]
date: 2019-10-21T19:20:04+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Photo by Franck V. on Unsplash"
  focal_point: "Smart"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Github
  url: https://github.com/henry32144/drlnd-continuous-control
  icon_pack: fab
  icon: github
- name: Report
  url: https://henry32144.github.io/drlnd-continuous-control/
  icon_pack: far
  icon: file-alt

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Currently, I use DDPG to solve the multi-agents version of this environment.