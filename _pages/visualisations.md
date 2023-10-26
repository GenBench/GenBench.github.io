---
permalink: /visualisations/
title: "Inside the taxonomy: visualisations"
excerpt: "Explore generalisation research in NLP visually"
toc: true
author_profile: false
layout: single_wide
toc_sticky: true
markdown: kramdown
header:
  <!-- overlay_image: /assets/images/unsplash-image-1.jpg -->
  overlay_color: "#268"

---

<!-- Load plotly.js into the DOM -->
<script src='https://cdn.plot.ly/plotly-2.11.1.min.js'></script>
<script type="text/javascript">window.PlotlyConfig = {MathJaxConfig: 'local'};</script>


On this page you can view the results of our review, which contains [taxonomy](/taxonomy) annotations of more than 400 \*ACL papers.
If you would like to contribute annotations for your paper or (new) papers you think are missing, please [contribute](/contribute).
You can view the entries considered for our review on our [references page](/references).
If you are curious about our conclusions based on these results, have a look at the results section of our [paper](https://www.nature.com/articles/s42256-023-00729-y)!

## In need of visualisations for your paper?
Are you writing a paper about generalisation in NLP and would you like to motivate your work with some graphics?
We would happily provide you with visualisations through the interactive graphs listed on this page.
If you hover over the graphs, you can click on the 📸 (camera) or 💾 (save) icons to download them in `.png` format, or you can contact us for custom adaptations of these graphs (email us at <a href="mailto:genbench@googlegroups.com">genbench@googlegroups.com</a>).

```
@Article{Hupkes2023,
  author={Hupkes, Dieuwke and Giulianelli, Mario and Dankers, Verna and Artetxe, Mikel and Elazar, Yanai 
  and Pimentel, Tiago and Christodoulopoulos, Christos and Lasri, Karim and Saphra, Naomi and Sinclair, Arabella 
  and Ulmer, Dennis and Schottmann, Florian and Batsuren, Khuyagbaatar and Sun, Kaiser and Sinha, Koustuv 
  and Khalatbari, Leila and Ryskina, Maria and Frieske, Rita and Cotterell, Ryan and Jin, Zhijing},
  title={A taxonomy and review of generalization research in NLP},
  journal={Nature Machine Intelligence},
  year={2023},
  month={Oct},
  day={01},
  volume={5},
  number={10},
  pages={1161-1174},
  abstract={The ability to generalize well is one of the primary desiderata for models of natural language processing (NLP), but what `good generalization' entails and how it should be evaluated is not well understood. In this Analysis we present a taxonomy for characterizing and understanding generalization research in NLP. The proposed taxonomy is based on an extensive literature review and contains five axes along which generalization studies can differ: their main motivation, the type of generalization they aim to solve, the type of data shift they consider, the source by which this data shift originated, and the locus of the shift within the NLP modelling pipeline. We use our taxonomy to classify over 700 experiments, and we use the results to present an in-depth analysis that maps out the current state of generalization research in NLP and make recommendations for which areas deserve attention in the future.},
  issn={2522-5839},
  doi={10.1038/s42256-023-00729-y},
  url={https://doi.org/10.1038/s42256-023-00729-y}
  }
```
[Download bib entry](../hupkes2023taxonomy.bib)

## Explore visualisations

###  Taxonomy overview

We provide two interactive plots that provide an overview of all five axes at the same time.

#### Sankey diagram
The taxonomy characterises research according to five axes. The Sankey diagram below illustrates the main relations between the axes that are most closely related, while illustrating the frequency of labels per class.
You can see, for instance, that:
- the most frequent motivation for generalisation research is 'practical', but practically motivated studies can still take on any type;
- generalisation research introducing a covariate data shift mostly focuses on the difference between train (or fine-tune) and test data;
- structural generalisation experiments are mostly motivated from a cognitive perspective, and are never about fairness;
- fully generated data is often used to create shifts between the train and test data.

NB: this plot renders best on relatively wide screens


<script type="module">
import sankeyData from '../plot_data/sankey.json' assert {type: "json" };


Plotly.newPlot('sankey', sankeyData.data, sankeyData.layout, {responsive: true} );
</script>

<div id='sankey'><!-- Plotly chart will be drawn inside this DIV --></div>

#### Chord diagram

If you would like to investigate the relations between all axes, take a look at the Chord diagram below. For readability purposes, we only illustrate connections that occurred more than 50 times.
Each axis has its own colour scheme, and the node labels indicate both the axis's name and the labels within that axis.
If you hover over a node or click on that node, the diagram highlights the connections to other nodes.


<div align="center">
  <iframe id="chord_diagram" style="display:block;height:max(900px,80vh);width:70%;border:none" scrolling=no frameborder="0" src="/visualisations/interactive_figures/chord_diagram.html"></iframe>
</div>

### Individual axes over time

Visualise how distribution over the axes values changes over time.
Use the radio buttons to indicate which axis you would like to view, and to choose how to normalise your plot.

<div>
  <iframe id="barplot_time_outer" style="height:750px;width:100%;border:none" scrolling=no frameborder="0" src="/visualisations/barplot_time.html"></iframe>
</div>


### Individual axes over tasks

Here, you can visualise how the different axes values are distributed over different tasks.
Use the radio buttons to indicate which taxonomy axis you would like to view, click on the tasks to remove them from the plot.


<div id="portrait">
  <iframe id="barplot_tasks_outer" style="height:60vh;width:100%;border:no;" scrolling=no frameborder="0" src="/visualisations/tasks_barplot.html"></iframe>
</div>

### Relations between axes in a heatmap

Generate heatmaps of the relations between the different axes.
Use the radio buttons to indicate which axis you would like on the x- and y-axis, and choose how to normalise your plot.

<div>
  <iframe id="heatmap_outer" style="height:750px;width:100%;border:none" scrolling=no frameborder="0" src="/visualisations/heatmap.html"></iframe>
</div>

Looking for a different kind of plot?
Let us know!
