---
title: mrsimulator
summary: A fast solid-state NMR spectrum simulation and analysis library.
tags:
  - Simulation
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: mrsimulator logo
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/deepanshs/mrsimulator
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

Shortly after the birth of Nuclear Magnetic Resonance (NMR) spectroscopy, it was realized that spin and spatial degrees of freedom could be manipulated on a time scale faster than the coherence lifetimes of the nuclear spin transitions. This led to an explosion of multi-pulse and sample reorientation methodologies in magnetic resonance for probing the structure and dynamics of matter over a wide range of length and time scales.

Numerical simulations of the NMR spectra from these methods have long been a critical part of their analyses. The most robust and rigorous numerical approaches employ the full density operator, ideal for dealing with finite pulse effects, weak to intermediate to strong couplings, non-commuting Hamiltonians, and relaxation and exchange processes. However, such approaches can be highly inefficient, particularly when Hamiltonians commute, pulses are ideal, and transverse relaxation can be treated as an ad-hoc line broadening. mrsimulator, an open-source python package, achieves high benchmarks in spectral simulations and analyses by limiting itself to these simpler situations. Fortunately, working within this limit only prevents mrsimulator from modeling spectra of a small fraction of popular NMR methods. The efficiency gains with this approach over conventional density operator simulations are tremendous.

In my work on this project I designed and built the singal processing library. This library allows the user to modify their simulated spectrum using various common signal processing functions, such as line broadening filters or baseline corrections, such that their simulated spectrum can better fit an experimental spectrum. As part of this work I contributed object oriented code that fit within the overall framework of the mrsimulator package. I also provided clear documentation and examples of code for all items.
