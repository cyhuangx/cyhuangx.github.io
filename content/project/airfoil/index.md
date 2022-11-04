---
title: Lagrangian Analysis of 2D Airfoils
summary: Separated flows past NACA 0012 airfoil and Eppler 423 airfoil was explored from Lagrangian perspectives.
tags:
  - Airfoil
date: '2022-08-01T00:00:00Z'

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



Velocity fields of flows over NACA 0012 airfoil and Eppler 423 airfoil with different angles of attack are obtained by direct numerical simulation. Attracting LCSs (unstable manifolds) are extracted by calculating backward finite-time Lyapunov exponent (FTLE) fields through integrating the trajectories of a uniform mesh of fluid particles backward in time. We also utilize Lagrangian-averaged vorticity deviation (LAVD) method to acquire coherent vortex boundaries and explore their evolution.


{{< video src="/videos/airfoil/NACA0012-10deg.mp4" controls="yes" >}}

NACA 0012 airfoil, Re=1000, AOA=10 deg, backward FTLE field.

{{< video src="/videos/airfoil/NACA0012-15deg.mp4" controls="yes" >}}

NACA 0012 airfoil, Re=1000, AOA=15 deg, backward FTLE field.

{{< video src="/videos/airfoil/NACA0012-20deg.mp4" controls="yes" >}}

NACA 0012 airfoil, Re=1000, AOA=20 deg, backward FTLE field.

![screen reader text](images/airfoil/NACA0012-LAVD.png "NACA 0012 airfoil, Re=1000, AOA=20 deg, LAVD field. The red point denotes the vortex center and the red closed curve denotes the vortex boundary.")

![screen reader text](images/airfoil/E423-FTLE.jpg "Eppler 423 airfoil, Re=40000, AOA=5 deg, backward FTLE field.")

