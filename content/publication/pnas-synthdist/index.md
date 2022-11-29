---
abstract: The power grid is going through significant changes with the
  introduction of renewable energy sources and the incorporation of smart grid
  technologies. These rapid advancements necessitate new models and analyses to
  keep up with the various emergent phenomena they induce. A major prerequisite
  of such work is the acquisition of well-constructed and accurate network
  datasets for the power grid infrastructure. In this paper, we propose a
  robust, scalable framework to synthesize power distribution networks that
  resemble their physical counterparts for a given region. We use openly
  available information about interdependent road and building infrastructures
  to construct the networks. In contrast to prior work based on network
  statistics, we incorporate engineering and economic constraints to create the
  networks. Additionally, we provide a framework to create ensembles of power
  distribution networks to generate multiple possible instances of the network
  for a given region. The comprehensive dataset consists of nodes with
  attributes, such as geocoordinates; type of node (residence, transformer, or
  substation); and edges with attributes, such as geometry, type of line (feeder
  lines, primary or secondary), and line parameters. For validation, we provide
  detailed comparisons of the generated networks with actual distribution
  networks. The generated datasets represent realistic test systems (as compared
  with standard test cases published by Institute of Electrical and Electronics
  Engineers (IEEE)) that can be used by network scientists to analyze complex
  events in power grids and to perform detailed sensitivity and statistical
  analyses over ensembles of networks.
slides: ""
url_pdf: uploads/pnas-synthdist-paper.pdf
publication_types:
  - "2"
authors:
  - admin
  - Anil Vullikanti
  - Samarth Swarup
  - Henning Mortveit
  - Virgilio Centeno
  - Arun Phadke
  - Vincent Poor
  - Madhav Marathe
author_notes:
  - Equal contribution
  - Equal contribution
  - Equal contribution
  - Equal contribution
  - Equal contribution
  - Equal contribution
  - Equal contribution
  - Equal contribution
publication: Proceedings of the National Academy of Sciences
summary: The availability of power distribution network datasets is essential to
  researchers when testing different control algorithms prior to their actual
  implementation and deployment on distribution systems. The proprietary nature
  of actual distribution system data effectively prevents them from being
  publicly available for use. Most educators and researchers rely on standard
  test systems published by Institute of Electrical and Electronics Engineers
  (IEEE), which neither are representative of actual distribution networks nor
  provide challenges in terms of the size of actual systems. We develop a
  framework that employs freely available data to construct ensembles of
  synthetic distribution networks resembling their physical counterparts with
  realistic scale and complexity. These synthetic networks are geographically
  embedded and include realistic residential demand profiles, and thus, they can
  be used to study smart grid applications.
url_dataset: https://github.com/rounak-meyur/synthetic-distribution/tree/master/output
url_project: ""
publication_short: PNAS
url_source: ""
url_video: ""
title: Ensembles of realistic power distribution networks
doi: https://doi.org/10.1073/pnas.2205772119
featured: true
tags: []
projects: []
image:
  caption: Framework for creating and validating ensembles of synthetic
    distribution network
  focal_point: ""
  preview_only: false
  filename: featured.png
date: 2022-10-11T00:00:00.000Z
url_slides: uploads/pnas-synthdist-slides.pdf
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: https://github.com/rounak-meyur/synthetic-distribution
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
