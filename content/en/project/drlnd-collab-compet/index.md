---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Collaboration and Competition"
summary: "Training agents to play Tennis game."
authors: ["ChengHan Wu"]
tags: ["Reinforcement Learning"]
categories: ["Course Projects"]
date: 2019-10-21T20:05:54+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Photo by Josephine Gasser on Unsplash"
  focal_point: "Smart"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Github
  url: https://github.com/henry32144/drlnd-collab-compet
  icon_pack: fab
  icon: github
- name: Report
  url: https://henry32144.github.io/drlnd-collab-compet/
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
In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.