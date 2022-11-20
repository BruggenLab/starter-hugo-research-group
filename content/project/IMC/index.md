---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Imaging Mass Cytometry (IMC)"
summary: "Imaging Mass Cytometry (IMC) ..."
authors:
      -
tags: []
categories: []
date: 2022-11-16T19:01:16+01:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

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
Imaging Mass Cytometry (IMC) is a spatial mass spectrometric approach which provide a comprehensive and multiparametric technique to investigate tissue with special and single cell resolution. This high dimensional tissue imaging system allows us to quantify up to 50 markers on single cells simultaneously with precise spatial resolution. In this technique tissue slices are labeled with metal conjugated antibodies and slides are ablate by laser to initiate a clump of particles which transport with inert gas to the mass spec that quantify the presence of each metal tag in a pixel. IMC-based methods could be applied on paraffine embedded tissue therefor a retrospective analysis with known results could be carried out. We utilize IMC technique in order to study skin tissue’s spatial structure and cellular compound.

Analysis

One of the crucial points in the system biology and immunology in to explore and exploit information from high dimensional datasets, in order to overcome this challenge, we use different statistical and image analysis tools and pipelines for a better fundamental understanding insights into disease. For pre-processing and single-cell segmentation we use ImcSegmentationPipeline and Dockerized multi-channel image processing framework (Steinbock) developed by Bodenmiller group and it is available on their Github repository. After single-cell generation all further analysis is performed using R bioconductor.

List for software’s and frameworks that we use to analyze our IMC data:

• histology topography cytometry analysis toolbox (histoCAT), steinbock, cytomapper and imcRtools all avialabe at (github.com/BodenmillerGroup).

• CellProfiler (www.cellprofiler.org) cell image analysis software

• Ilastik (www.ilastik.org) interactive learning and segmentation toolkit

• DeepCell (https://github.com/vanvalenlab/deepcell-tf) deep learning library for single-cell analysis of biological images

• Bioconductor an open source software for bioinformatics (www.bioconductor.org/)
