---
title: "Portfolio"
date: 2018-10-23T17:48:20-04:00
categories:
- Data
- Visualization
tags:
- Data
- Visualzation
keywords:
- tech
comments:       false
showMeta:       false
showActions:    false
thumbnailImage: /images/portfolio/MultiNetwork.png
---

This is a small gallery showing some of nice graphics that I have generated.

Overall I think that data visualization is amazing and beautiful and I feel like having a small collection of them would be nice in the future for inspiration (mine and anyone else looking at them).
It is to note that labels are poorly labelled on purpose because some data has not been published and I would like to keep it as confidential as posible while still showing the visualization.

{{< image classes="fancybox center fig-75" src="/images/portfolio/CDKL5Volcano.png" group="portfolio" title="Volcano Plot Labelling a subset of relevant genes" >}}
{{< image classes="fancybox center fig-75" src="/images/portfolio/GOLollipop.png" group="portfolio" title="Lollipop chart showing over-represented gene ontologies product of three preparations of the same plant sample" >}}
{{< image classes="fancybox center fig-75" src="/images/portfolio/Heatmap.png" group="portfolio" title="Heatmap summarising the changes with respect to a control of a subset of proteins" >}}
{{< image classes="fancybox center fig-75" src="/images/portfolio/MotifHighlightVolcano.png" group="portfolio" title="Labelled Volcano Plot" >}}
{{< image classes="fancybox center fig-75" src="/images/portfolio/MultiNetwork.png" group="portfolio" title="Network showing the protein-protien interactions at several time points of a proteomics experiment" >}}

Final remarks.
Most of the plots are done using ggplot2 in R and for network data the processing is usually done in R and then passed to Cytoscape (show some love to those projects).
