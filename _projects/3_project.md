---
layout: page
title: Generating Useful Hierarchical Representations 
description: Theory and application of hierachical VAEs and AA
img: /assets/img/hie_vaes.jpg
importance: 3
category: work
---

Representation learning is a central topic in machine learning and has seen tremendous progress over the years. Probabilistic latent variable models are particularly well suited in this regard, as they naturally introduce a latent representation of the input while generating new data and accounting for uncertainty . Variational Autoencoders (VAEs) are a class of probabilistic latent variable models that learn a stochastic encoder and decoder, parametrized by a neural network, that map the input into a latent representation and back. VAEs have been a conceptual advance in the field, but in practice, they have shown limitations, in particular:
* they do not always generate useful latent spaces, they might even completely ignore the latent variable in the reconstruction process: a phenomenon known as “posterior collapse”
* they generate synthetic data of worse quality (i.e. blurriness in images) compared to other generative models such as diffusion models 

A promising line of research addressing both these shortcomings is enforcing a hierarchy of latent variables. The main rationale is that if a latent variable model adopts a hierarchical structure, it might impose an inductive bias, limit the range of possible models, and ultimately facilitate the flow of information between latent variables and observable data. Another advantage of this kind of architecture is that it provides a more expressive latent space, which improves generative performances.

My goal in this project is to study better the theoretical foundations of those kind of models and apply them to large atlas-scale single-cell datasets with millions of profiled cell. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/hie_vaes.jpg" title="hierarchical vaes" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

