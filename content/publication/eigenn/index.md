---
title: "Machine learning full NMR chemical shift tensors of silicon oxides with equivariant graph neural networks"
authors:
- admin
- Mingjian Wen
- Kristin Persson
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-03-02T00:00:00Z"
doi: "https://doi.org/10.1021/acs.jpca.2c07530"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*The Journal of Physical Chemistry A, 127*(10)"
publication_short: ""

abstract: The nuclear magnetic resonance (NMR) chemical shift tensor is a highly sensitive probe of the electronic structure of an atom and furthermore its local structure. Recently, machine learning has been applied to NMR in the prediction of isotropic chemical shifts from a structure. Current machine learning models, however, often ignore the full chemical shift tensor for the easier-to-predict isotropic chemical shift, effectively ignoring a multitude of structural information available in the NMR chemical shift tensor. Here we use an equivariant graph neural network (GNN) to predict full 29Si chemical shift tensors in silicate materials. The equivariant GNN model predicts full tensors to a mean absolute error of 1.05 ppm and is able to accurately determine the magnitude, anisotropy, and tensor orientation in a diverse set of silicon oxide local structures. When compared with other models, the equivariant GNN model outperforms the state-of-the-art machine learning models by 53%. The equivariant GNN model also outperforms historic analytical models by 57% for isotropic chemical shift and 91% for anisotropy. The software is available as a simple-to-use open-source repository, allowing similar models to be created and trained with ease.

# Summary. An optional shortened abstract.
summary: "Most nuclear magnetic resonance (NMR) modeling is focused entirely on the isotropic nuclear shielding. The NMR measurement, however, probes a tensor property and significant stuctural information is lost if we only look at the isotropic portion of this tensor. Unfortunately, modeling a tensor is not straightforward, as tensor symmetries must be taken into account when building the model, and this has been impossible up until now. In this work we introduce a graph neural network (GNN) that is capable of predicting NMR tensors. We further benchmark this model and take a deep dive into the best practices for designing and assessing tensor based models.

My main contributions to this work are (1) curation and processing of data set, (2) building, training, and assessments of all models, (3) developing tensor evaluation frameworks and comparisons to existing frameworks."


tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://pubs.acs.org/doi/pdf/10.1021/acs.jpca.2c07530
url_code: 'https://github.com/mjwen/matten'
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
Most nuclear magnetic resonance (NMR) modeling is focused entirely on the isotropic nuclear shielding. The NMR measurement, however, probes a tensor property and significant stuctural information is lost if we only look at the isotropic portion of this tensor. Unfortunately, modeling a tensor is not straightforward, as tensor symmetries must be taken into account when building the model, and this has been impossible up until now. In this work we introduce a graph neural network (GNN) that is capable of predicting NMR tensors. We further benchmark this model and take a deep dive into the best practices for designing and assessing tensor based models.

My main contributions to this work are (1) curation and processing of data set, (2) building, training, and assessments of all models, (3) developing tensor evaluation frameworks and comparisons to existing frameworks.

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
