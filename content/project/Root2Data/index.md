---
title: "ROOT2Data: From ROOT to AI-Ready Data"

summary: ROOT2Data is an open source Python toolset for converting ROOT files to hdf5, sqlite & parquet data formats.


tags:
- Open Source
#- Data Analytics
#- Temperature dependent
#- Time dependent
#- Coupling
#- MBD
#- Adhesion
#- Cohesion
#- EEPA
#- EBBM

#date: 2025-08-25
date: 2025-08-25
publishDate: 2025-08-25
lastmod: 2025-08-25

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Schematic overview of the root2data conversion workflow.
  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/jp_morr
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: ""

# gallery captions
#gallery_item:
#- album: post_doc
#  image: jenike_cell.png
#  caption: Comparison in simulations (force network, geometry positions and particle velocities) of fully #coupled (with rotation) MBD simulation of Jenike cell against simplified vertical stress application only
#- album: post_doc
#  image: jenike_stresses.png
#  caption: Comparison in stress fields for fully coupled (with rotation) MBD simulation of Jenike cell against simplified vertical stress application only
#- album: post_doc
#  image: temporally_scaled_uniaxial.jpg
#  caption: Comparison of DEM Consolidation Time against experimental dataset

---

# Introduction
---
High-energy physics relies on the ROOT format to store complex event data—but this structure can be limiting for modern AI workflows. root2data bridges this gap by transforming ROOT files into flexible, machine learning–ready formats like Parquet, SQLite, and HDF5.

The software is publicly available on [Zenodo](https://doi.org/10.5281/zenodo.14281076) and [Github](https://github.com/appINPP/root2data).


---