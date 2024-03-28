---
title: Plot metadata blocks for the carbapenamase genes
description:  Plot metadata blocks for the carbapenamase genes CTX-M-15, NDM-1, KPC and OXA. What are the prevalent AMR mechanisms detected ?
authors:
    - Nabil-Fareed Alikhan
date: 2024-03-25
---

We have already [created charts to visualise data](./step-3.md) in our Microreact projects. Another useful feature of Microreact is to overlay information as 'Metadata blocks' alongside phylogenetic trees. This is the easiest way to do direct comparison with the evolutionary relationships (phylogeny) with other information. In this recipe, we will show the presence carbapenamase genes alongside the provided phylogenetic tree, just like the figure below. 

![Final output](tutorial/final-tree-gene.png)

## Microreact features demonstrated

* Showing metadata along side a phylogeny
* Customising metadata blocks


## Tutorial

You should be using the project we opened in the previous steps. Please see [Creating an editable project](./step-1.md) and follow the instructions if not. Select the "Kpn Colombia" view. Press the icon on the top right of the tree panel.

![Task 4: Plot metadata blocks for CTX-M-15, NDM-1, KPC and OXA genes. What are the prevalent AMR mechanisms detected ? Step 1: Press the icon on the top right of the tree panel.](tutorial/show%20metadata.png){width="70%"}

In the Metadata blocks dropdown list, tick all boxes containing KPC, NDM, VIM, OXA and CTX-M-15 genes. In this same menu, you can also customise the block feature scaling with options like 'Block headers' and 'Block Size'. You can export the chart as a seperate image (svg or png) by using the hamburger menu button in the top right. 

![Task 4: Plot metadata blocks for CTX-M-15, NDM-1, KPC and OXA genes. What are the prevalent AMR mechanisms detected ? Step 2: In the Metadata blocks dropdown list, tick all boxes containing KPC, NDM, VIM, OXA and CTX-M-15 genes.](tutorial/metadata%20block%20select%20genes.png){width="70%"}

The tree panel will show metadata columns aligned with the tree tips. Yellow indicates presence of a certain gene and green indicates absence. If you need to refer to the legend click the Legend tab on the right, and scroll down. In the panel shown here, it appears that the most common genes present (in yellow) are KPC-2, KPC-3, NDM-1 and CTX-M-15. 

![Task 4: Plot metadata blocks for CTX-M-15, NDM-1, KPC and OXA genes. What are the prevalent AMR mechanisms detected ? Step 3: The tree panel will show metadata columns. Yellow indicates presence of a certain gene and green indicates absence. In the panel shown here, it appears that the most common genes present are KPC-2, KPC-3, NDM-1 and CTX-M-15.](tutorial/metadata_blocks.png)

