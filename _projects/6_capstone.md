---
layout: page
title: AI Book Explorer
description: NLP pipeline using sentence embeddings, UMAP, and LLM-assisted clustering for thematic analysis. Capstone with Cal State LA.
img: assets/img/BookThumb.png
importance: 5
category: research
related_publications: false
---

An end-to-end NLP pipeline that maps 21,000+ books into thematic clusters: SentenceTransformers embeddings, UMAP dimensionality reduction, and LLM-assisted labeling — with semantic search, cluster exploration, and hierarchical dendrograms. Capstone project developed in collaboration with **California State University, Los Angeles**.

**Stack:** SentenceTransformers, UMAP, Optuna, Ollama, Plotly, Python.

<div style="margin: 1.2rem 0;">
  <a href="https://github.com/HiramZ04/Cal-State-UMAP_Clustering" target="_blank" style="display:inline-block;padding:0.5rem 1.3rem;background:var(--global-theme-color);color:#fff;border-radius:6px;font-weight:600;text-decoration:none;">💻 Code on GitHub</a>
</div>

---

<video autoplay muted loop controls style="width:100%;border-radius:8px;margin-bottom:1.5rem;">
  <source src="/assets/img/BookExplorerVideo.mp4" type="video/mp4">
</video>

<div class="row mt-2">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/cluster_selection.png" title="Semantic search — query mapped onto the UMAP cluster space" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/dendro.png" title="Dendrogram — hierarchical structure of book clusters" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
