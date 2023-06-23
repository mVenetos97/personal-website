---
title: nmrcryspy
summary: A machine-learning-enhanced toolbox for NMR crystallographic refinements.
tags:
  - Machine Learning
date: '2017-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: nmrcryspy logo
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/mVenetos97/nmrcryspy
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''
---

For crystalline solids, the gold standard of measuring a material's structure is with single crystal X-ray diffraction (XRD) measurements. Oftentimes, however, the single crystal XRD measurement is unavailable. For example, many pharmaceutical molecules are only available in powder form and powder XRD is significantly less accurate. For cases like these, we must use additional measurements, most commonly solid-state NMR as NMR does not require perfect crystallinity. By combining NMR and powder XRD measurements, along with quantum chemical calculations we can better refine and elucidate the structures of difficult-to-measure materials.

Unfortunately, many workflows to do this structure refinement are extremely computationally expensive, requiring days to weeks of compute time on state-of-the-art supercomputer clusters. As a result, these methods are difficult to scale to high throughput and can often only be used for small and simple materials.

This python package, nmrcryspy, is a toolkit meant to make these refinement workflows easier to perform. This package allows users to replace the time-intensive quantum chemical calculations with cutting-edge machine learning (ML) algorithms. In the accompanying manuscript we show that a refinement that took a week to perform running on a supercomputer before only took 2 hours when running on a personal laptop. Furthermore, we found that the ML based refinement yielded a better structure as the ML is trained using a higher quality level of quantum calculation than what is feasible if doing the refinement using quantum chemical calculations instead.

