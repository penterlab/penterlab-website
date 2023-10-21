---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

To understand co-evolution of leukemic and immune cell populations, we are interested in (i) **lineage-tracing techniques 
that leverage natural genetic barcodes** to map out clonal evolution following (immuno)-therapeutic bottlenecks such as 
allogeneic stem cell transplantation, and (ii) multi-omics approaches to define the **phenotypes and specificities of 
therapeutically relevant T cell populations**. 

{% include section.html %}

## Lineage-tracing using natural genetic barcodes

The availability of approaches to resolve genetic and phenotypic information within the same cell opens up 
opportunities to better understand how immune resistance mechanisms develop that provide selective advantage 
and fuel clonal evolution. 
We use multi-omics single cell data to dissect longitudinal changes in the cell state of leukemic clones defined by natural genetic barcodes
and to gain novel insights into mechanisms that underpin relapse after immunotherapy. 
We are also excited about the possibility to integrate multiple genetic barcodes (mitochondrial and somatic nuclear DNA mutations,
copy number changes, expressed germline single nucleotide polymorphisms) to track rare malignant cells and to distinguish
donor- from recipient-derived cells in the post-transplant context. 

{%
  include figure.html
  image="images/lineage_tracing.jpeg"
  caption="Natural genetic barcodes dissect clonal evolution (Penter, Gohil & Wu, Frontiers Immunology 2022)"
  link="https://doi.org/10.3389/fimmu.2021.788891"
  width="400px"
%}

{%
  include citation.html
  lookup="doi:10.1158/2159-8290.CD-21-0276"
%}

{%
  include citation.html
  lookup="doi:10.1158/0008-5472.CAN-22-0275"
%}

{% include section.html %}

## Leukemia-specific T cell responses 

While immune checkpoint blockade and adaptive T cell therapy is reshaping solid tumors, 

{%
  include figure.html
  image="images/Tcell_phenotypes.jpeg"
  caption="T cell phenotypes in blood and solid malignancies (Penter et al., Blood 2023)"
  link="https://doi.org/10.1182/blood.2022018246"
  width="400px"
%}

{%
  include citation.html
  lookup="doi:10.1182/blood.2022018246"
%}

{%
  include citation.html
  lookup="doi:10.1182/blood.2021010867"
%}


## Featured

{% include list.html component="card" data="projects" filters="group: featured" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filters="group: " style="small" %}
