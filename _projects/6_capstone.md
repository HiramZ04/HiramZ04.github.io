---
layout: page
title: AI Book Explorer
description: NLP pipeline using sentence embeddings, UMAP, and LLM-assisted clustering for thematic analysis. Capstone with Cal State LA.
img: assets/img/BookThumb.png
importance: 7
category: research
related_publications: false
---

An end-to-end NLP pipeline that maps 21,000+ books into thematic clusters: SentenceTransformers embeddings, UMAP dimensionality reduction, and LLM-assisted labeling — with semantic search, cluster exploration, and hierarchical dendrograms. Capstone project developed in collaboration with **California State University, Los Angeles**.

**Stack:** SentenceTransformers, UMAP, Optuna, Ollama, Plotly, Python.

<div style="margin: 1.2rem 0;">
  <a href="https://github.com/HiramZ04/Cal-State-UMAP_Clustering" target="_blank" style="display:inline-block;padding:0.5rem 1.3rem;background:var(--global-theme-color);color:#fff;border-radius:6px;font-weight:600;text-decoration:none;">💻 Code on GitHub</a>
</div>

---

<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;border-radius:8px;margin-bottom:1.5rem;">
  <iframe src="https://www.youtube.com/embed/fRBPEUHexRg?autoplay=1&mute=1" title="AI Book Explorer — NLP Demo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;"></iframe>
</div>

<div class="row mt-2">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/cluster_selection.png" title="Semantic search — query mapped onto the UMAP cluster space" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/dendro.png" title="Dendrogram — hierarchical structure of book clusters" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
