---
title: "Assessing the Accuracy of Density Functional Approximations for Predicting Hydrolysis Reaction Kinetics"
authors:
- Alexander Epstein
- Evan Spotte-Smith
- admin
- Oxana Andriuc
- Kristin Persson
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-02-10T00:00:00Z"
doi: "https://doi.org/10.1021/acs.jctc.3c00176"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Chemical Theory and Computation, 19*(11)"
publication_short: ""

abstract: Hydrolysis reactions are ubiquitous in biological, environmental, and industrial chemistry. Density functional theory (DFT) is commonly employed to study the kinetics and reaction mechanisms of hydrolysis processes. Here, we present a new data set, Barrier Heights for HydrOlysis - 36 (BH2O-36), to enable the design of density functional approximations (DFAs) and the rational selection of DFAs for applications in aqueous chemistry. BH2O-36 consists of 36 diverse organic and inorganic forward and reverse hydrolysis reactions with reference energy barriers ΔE‡ calculated at the CCSD(T)/CBS level. Using BH2O-36, we evaluate 63 DFAs. In terms of mean absolute error (MAE) and mean relative absolute error (MRAE), ωB97M-V is the best-performing DFA tested, while MN12-L-D3(BJ) is the best-performing pure (nonhybrid) DFA. Broadly, we find that range-separated hybrid DFAs are necessary to approach chemical accuracy (0.043 eV). Although the best-performing DFAs include a dispersion correction to account for long-range interactions, we find that dispersion corrections do not generally improve MAE or MRAE for this data set.

# Summary. An optional shortened abstract.
summary: Very few benchmarks exist for reaction barriers, and even fewer exist for reaction barriers for hydrolysis reactions. In this work we develop a dataset of 36 chemically diverse hydrolysis transition state barrier heights at CCSD(T)/CBS level of theory. We then benchmark 63 density functionals on these reactions to determine the best functionals for the prediction of transition state energy. In this work my main contributions were (1) designing the dataset and choosing reactions to fully capture the diverse space of hydrolysis reactions, (2) establishing theoretical methodology for the calculation of CCSD(T)/CBS level of theory, and (3) statistical analysis of the results.


tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://chemrxiv.org/engage/api-gateway/chemrxiv/assets/orp/resource/item/63e3d97b3067856f18bb18d0/original/assessing-the-accuracy-of-density-functional-approximations-for-predicting-hydrolysis-reaction-kinetics.pdf
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: "" #example
---

Very few benchmarks exist for reaction barriers, and even fewer exist for reaction barriers for hydrolysis reactions. In this work we develop a dataset of 36 chemically diverse hydrolysis transition state barrier heights at CCSD(T)/CBS level of theory. We then benchmark 63 density functionals on these reactions to determine the best functionals for the prediction of transition state energy. 

In this work my main contributions were (1) designing the dataset and choosing reactions to fully capture the diverse space of hydrolysis reactions, (2) establishing theoretical methodology for the calculation of CCSD(T)/CBS level of theory, and (3) statistical analysis of the results.

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
