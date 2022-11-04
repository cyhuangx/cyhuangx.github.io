---
title: Tadpole Locomotion Simulation
summary: Using a rotationally oscillating cylinder with an attached filament to simulate the tadpole swimming.
tags:
  - Biological Swimming
date: '2022-03-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

#image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: "https://twitter.com/georgecushen"
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---



Tadpole swimming was investigated by simulating flow past a rotationally oscillating cylinder with an attached filament using open-source software IBAMR. The cylinder is forced to oscillate as a sinusoidal function of time. The attached filament with different bending rigidity moves passively under the influence of the oscillating cylinder and the surrounding flow field. The Reynolds number is set as 150 based on the diameter of the cylinder.


{{< video src="/videos/tadpole/rigid.mp4" controls="yes" >}}

A rotationally oscillating cylinder with a short and rigid filament.

{{< video src="/videos/tadpole/flexible.mp4" controls="yes" >}}

A rotationally oscillating cylinder with a long and flexible filament.

