---
title: Structural Validation of Synthetic Power Distribution Networks Using the
  Multiscale Flat Norm
subtitle: Using computational geometry to compare network structures
abstract: >-
  We study the problem of comparing a pair of geometric networks that may not be
  similarly defined, i.e., when they do not have one-to-one correspondences
  between their nodes and edges. Our motivating application is to compare power
  distribution networks of a region. Due to the lack of openly available power
  network datasets, researchers synthesize realistic networks resembling their
  actual counterparts. But the synthetic digital twins may vary significantly
  from one another and from actual networks due to varying underlying
  assumptions and approaches. Hence the user wants to evaluate the quality of
  networks in terms of their structural similarity to actual power networks. But
  the lack of correspondence between the networks renders most standard
  approaches, e.g., subgraph isomorphism and edit distance, unsuitable.


  We propose an approach based on the multiscale flat norm, a notion of distance between objects defined in the field of geometric measure theory, to compute the distance between a pair of planar geometric networks. Using a triangulation of the domain containing the input networks, the flat norm distance between two networks at a given scale can be computed by solving a linear program. In addition, this computation automatically identifies the 2D regions (patches) that capture where the two networks are different. We demonstrate our approach on a set of actual power networks from a county in the USA. Our approach can be extended to validate synthetic networks created for multiple infrastructures such as transportation, communication, water, and gas networks.
slides: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
publication_types:
  - "1"
authors:
  - admin
publication: International Conference on Computational Science
featured: false
projects:
  - Synthetic Power Distribution Networks
image:
  caption: ""
  focal_point: ""
  preview_only: false
summary: ""
url_dataset: "#"
url_project: ""
publication_short: ICCS 2023
url_source: "#"
url_video: "#"
doi: https://doi.org/10.1007/978-3-031-36027-5_5
tags:
  - Source Themes
date: 2023-07-05T17:21:34.605Z
url_slides: ""
links:
  - name: Custom Link
    url: http://example.org
publishDate: 2017-01-01T00:00:00.000Z
url_poster: "#"
url_code: https://github.com/wowchemy/wowchemy-hugo-themes
---
