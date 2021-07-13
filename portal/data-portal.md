---
description: A general overview of the portal and how to navigate it
---

# Find, Download, and Explore Data

## Find Data

The [cellxgene Data Portal](https://cellxgene.cziscience.com/) is SaaS data publishing platform that is optimized for the access, exploration, and reuse of single cell data that adhere to a common, minimal schema that facilitates rapid, intuitive exploration, combination, and integration. 

When enter the Data Portal, you land on the Collections Page, which lists the Collections hosted on the Data Portal and tissue, assay, disease, organism, and cell count metadata describing them. Each Collection describes a publication associated with one or more datasets.

![Cellxgene home page](../.gitbook/assets/image%20%288%29.png)

{% hint style="info" %}
**Note**: We are adding search and filter capability to the the Data Portal. For now, the current best way to find datasets from a particular author or tissue is to `CTRL + F` to find matching text on the page.
{% endhint %}

Clicking on a Collection name sends you to that collection's page, which contains a description, key links, and the datasets of the Collection: 

![An example Collection from the Teichmann group](../.gitbook/assets/image%20%286%29.png)

Each dataset is described by the same metadata available at the collection level. In addition, there are buttons \(far right\) that enable download and exploration of each dataset:

![Dataset entry in a collection page](../.gitbook/assets/image%20%283%29.png)

## ![](../.gitbook/assets/download.svg) Download Data

Clicking the download button brings up a dialog that enables a dataset to be downloaded in `h5ad` \(AnnData v0.7\), `loom`, and `rds` \(Seurat v3\) formats. All datasets adhere to the cellxgene [single cell annotated data schema](https://github.com/chanzuckerberg/single-cell-curation/blob/main/schema/2.0.0/corpora_schema.md). Datasets can either be downloaded via the browser by clicking the blue download button or via your command link by pasting the provided curl command. 

![Download dialog box](../.gitbook/assets/image%20%285%29.png)

## ![](../.gitbook/assets/explore.svg) Explore Data

Clicking the explore button launches the Cellxgene Explorer in a new tab:

![](../.gitbook/assets/cellxgene_colored_hcl.png)

To learn how to explore and analyze a dataset using the Cellxgene Explorer, please see the [Explore Data](../explore-data/the-exploration-interface.md) section of this documentation.

## History

The Data Portal evolved from the [COVID-19 data portal](https://www.covid19cellatlas.org/), a collaboration with the Wellcome Sanger Institute and The Human Cell Atlas that was developed to host single cell datasets that were useful to analyze how SARS-CoV2 infects cells in the face of the 2020 global pandemic. Since then, the cellxgene team has reacted to the need for a more generalized system that increases access to single cell data.

