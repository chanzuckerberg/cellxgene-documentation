---
description: Explaining the capabilities of the cellxgene's hosted and desktop explorers
---

# The Exploration Interface

Cellxgene's user interface organizes single cell data similarly to how it is organized in single cell data formats. The left hand side displays sample metadata \(observations\). The right hand side contains variable metadata \(usually genes\). The center displays the embedding, where cell is a point. UMAP and tSNE are common embeddings, which place cells based on their local distances in gene expression space. Cells from spatial data can also be displayed using each cell's \(x, y\) coordinates.

![](../.gitbook/assets/image%20%2819%29.png)

This highlights important cellxgene functionality:

![Cellxgene essential buttons](../.gitbook/assets/image%20%289%29.png)

The cellxgene toolbar buttons provide the following functionalities:

![Cellxgene toolbar](../.gitbook/assets/image%20%2814%29.png)

1. **Subset** the cells based on current selection \(based on categorical, numerical, or manual\). Only active when a selection is active.
2. **Reset to Whole**. Get the complete set of cells. Only active when a subset is currently active.
3. **Lasso** selection of cells on the plot \(manual selection\).
4. **Zoom** and move embedding plot.
5. **Display category names** of a selected categorical metadata field over the embedding.
6. **Clip outlier** values.
7. **Undo**.
8. **Redo**.

The following section, [How to Explore Data](how-to-explore-data.md), describes how these features can be used in combination to analyze and explore single cell data.

