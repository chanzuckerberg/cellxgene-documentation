---
description: >-
  This page displays two new media types (slideshow and movie) that we could use
  to demonstrate vignettes of cellxgene features.
---

# Vignette Media Test

These are initial attempts designed only to demonstrate media types. Both the slideshow and the movie could be annotated to highlight the actions being taken. I've annotated the first slide of the slideshow to provide an example. 

The vignettes both demonstrate the cross-filter functionality of cellxgene, which enables you to explore how one categorical variable is distributed in terms of another. The below vignettes use the [tabula muris senis dataset](https://cellxgene.cziscience.com/e/48b37086-25f7-4ecd-be66-f5bb378e3aea.cxg/), which you can click to follow along, and explore which animals the liver sub-tissues were identified in.

The vignette walks through the following steps \(numbers refer to slides\):

* \(1\) Color by `tissue` to reveal the different tissues of the dataset and then \(2\) Expand the `tissue` category to see the labels and cell abundances of each tissue
* Subset to only `liver` cells by \(3\) deselecting all cells by clicking the check box next to `tissue` to deselect all cells, \(4\) selecting `liver` cells by selecting the check box next to `liver`, and \(5\) clicking the `subset` button 
* \(7\) Examining the sub-tissues that remain after subsetting by clicking `expand` by `subtissue` and then coloring by `subtissue`
* \(8\) Coloring by `mouse.id` to reveal the proportion of each sub-tissue that comes from each donor mouse. In this case the result reveals a data curation issue that we know about \(multiple different `hepatocyte` fields should be harmonized and combined!\) and will take care of in our schema 2.0.0 upgrade, which is in progress.

**The question we have is: Between the slideshow and video below, which media type should we use to create vignettes for cellxgene?** 

{% embed url="https://docs.google.com/presentation/d/e/2PACX-1vSNyqJhC\_4huJLCaKZp6YOQcm0F0m603WG7R2\_G-5yKf5yAaxOt\_xGVE4qPZ7-TqmqSYosIH1R-5Txe/pub?start=false&loop=false&delayms=3000" caption="Note: to enter full screen, click the vertical ellipsis and select \"Enter full screen\"." %}

{% embed url="https://www.youtube.com/watch?v=IRYVnJ9C4EQ" %}



