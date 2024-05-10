---
layout: page
title: Multi-Omics Deep Archetypal Analysis
description: Finding a way to keep interpretability in highly non-linear dimensionality reduction
img: /assets/img/deepaa.jpg
importance: 1
category: work
redirect: https://github.com/sottorivalab/midaa

---

High-throughput multi-omic molecular profiling allows probing biological systems at unprecedented resolution. However, the integration and interpretation of high-dimensional, sparse, and noisy multimodal datasets remains challenging. Deriving new biology using current methods is particularly difficult because they are not based on biological principles, but instead focus exclusively on a dimensionality reduction task. We have developed introduce [MIDAA](https://github.com/sottorivalab/midaa) (Multiomic Integration with Deep Archetypal Analysis), a framework that combines archetypal analysis, an approach grounded in biological principles, with deep learning. Using the concept of archetypes that are based on evolutionary trade-offs and Pareto optimality – MIDAA finds extreme data points that define the geometry of the latent space, preserving the complexity of biological interactions while retaining an interpretable output.



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/deepaa_hr.jpg" title="Multi-Omics Deep Archetypal Analysis" class="img-fluid rounded z-depth-1" %}
    </div>
</div>