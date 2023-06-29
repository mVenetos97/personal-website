---
title: "Effective Local Geometry Descriptor for 29Si NMR Q4 Anisotropy"
authors:
- admin
- Shyam Dwaraknath
- Kristin Persson
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-08-26T00:00:00Z"
doi: "https://doi.org/10.1021/acs.jpcc.1c04829"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*The Journal of Physical Chemistry C, 125*(35)"
publication_short: ""

abstract: The nuclear shielding anisotropy, ζ, is a useful nuclear magnetic resonance (NMR) shielding tensor parameter in describing the extent of electron cloud distortion about an atom. Despite the advantages afforded by NMR in structural characterization, the relationship between ζ and local structure of an atom in high-symmetry environments, such as Si–Q4 sites, is poorly understood. Here, we use a data-driven approach combining random forest feature ranking and the Sure Independence Screening and Sparsifying Operator (SISSO) approach to derive a simple and accurate geometric descriptor for ζ with a root-mean-squared prediction error of 6.77 ppm and an R2 of 0.761. We then apply this descriptor to describe the local geometric distortion of zeolites Sigma-2 and silica-ZSM-5 whose chemical shift anisotropy tensor has been reported. We envision that this geometric descriptor will allow for structural description and refinement in previously difficult-to-describe materials.

# Summary. An optional shortened abstract.
summary: "In 2007 measuring the chemical shift anisotropy (CSA) tensor in highly symmetric silica materials became possible. In that original study, stuctural relationships between silicon geometry and the tensor anisotropy were explored but nothing was found. The authors at the time deemed the structure-anisotropy relationship impossible (or at least extremely difficult) to model analytically. Modeling something such as the anisotropy helps a great deal during structure elucidation studies as it is an additional piece of information we can use to determine the structure, and is thus something we are interested in modeling. Through a combination of theory-based feature engineering and using machine learning techniques like symbolic regression and feature importance analysis, we have developed an interpretable analytical model for the relationship between silicon geometry and anisotropy.

My main contributions to this work are (1) curation and processing of data set, (2) developing the features used in the feature engineering phase, (3) using a combination of random forests and symbolic regression to determine a functional form for a descriptor of silicon anisotropy."


tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://doi.org/10.1021/acs.jpcc.1c04829
# url_code: ''
url_dataset: 'https://next-gen.materialsproject.org/contribs/projects/lsdi_vasp_si29'
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
In 2007 measuring the chemical shift anisotropy (CSA) tensor in highly symmetric silica materials became possible. In that original study, stuctural relationships between silicon geometry and the tensor anisotropy were explored but nothing was found. The authors at the time deemed the structure-anisotropy relationship impossible (or at least extremely difficult) to model analytically. Modeling something such as the anisotropy helps a great deal during structure elucidation studies as it is an additional piece of information we can use to determine the structure, and is thus something we are interested in modeling. Through a combination of theory-based feature engineering and using machine learning techniques like symbolic regression and feature importance analysis, we have developed an interpretable analytical model for the relationship between silicon geometry and anisotropy.

My main contributions to this work are (1) curation and processing of data set, (2) developing the features used in the feature engineering phase, (3) using a combination of random forests and symbolic regression to determine a functional form for a descriptor of silicon anisotropy.

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
