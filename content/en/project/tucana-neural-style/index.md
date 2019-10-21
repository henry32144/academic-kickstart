---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Tucana Neural Style"
summary: "This website stylize image by several neural style transfer methods."
authors: ["ChengHan Wu", "WeiZuo Lin", "ChihChun Chen"]
tags: ["Deep Learning", "Website"]
categories: ["Projects"]
date: 2019-10-21T19:30:23+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Screenshot"
  focal_point: "Smart"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Github
  url: https://github.com/henry32144/neural-style
  icon_pack: fab
  icon: github
- name: Demo
  url: https://youtu.be/jeFk4GXkaPs
  icon_pack: fab
  icon: youtube


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
This website includes three kinds of transformations.

**Fast Neural Style**

The fast neural style implementation is based on [fast-neural-style-keras](https://github.com/misgod/fast-neural-style-keras) by misgod, We made some changes to it, and this method is base on [Perceptual Losses for Real-Time Style Transfer and Super-Resolution](http://cs.stanford.edu/people/jcjohns/eccv16/) by Johnson et al.

In the current version, We replace some of the Conv2D layer to Depth-wise separable convolutions in the image transformation net. 

**Style Swap**

The style swap layer is from [WCT-TF](https://github.com/eridgd/WCT-TF) by eridgd, the original paper is [Fast Patch-based Style Transfer of Arbitrary Style](https://arxiv.org/abs/1612.04337) by Chen et al.

**Mask Style**

We use [Mask R-CNN](https://github.com/matterport/Mask_RCNN) which is implemented by [matterport](https://github.com/matterport), the original paper of Mask R-CNN is [Mask R-CNN](https://arxiv.org/abs/1703.06870) by He et al.