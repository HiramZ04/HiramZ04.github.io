---
layout: page
title: Quantum Rings — MIT iQuHACK 2026
description: ML models predicting quantum circuit runtime and fidelity threshold from QASM features. MIT iQuHACK 2026 — 3rd place, Quantum Rings Challenge.
img: assets/img/MIT3.jpeg
importance: 7
category: hackathon
related_publications: false
---

**iQuHACK** is the largest quantum computing hackathon in the United States, hosted by MIT iQuISE with 400+ in-person competitors at MIT. Our team **Popeye's** placed **3rd in the Quantum Rings Challenge**.

The challenge: use machine learning to predict two key properties of quantum algorithms directly from their circuit structure — without running them. Circuits were provided in **QASM (Quantum Assembly Language)**, from which we extracted features to train our models:

- **Runtime regressor** — predicts how long a circuit will take to simulate. **R² = 0.78**
- **Threshold classifier** — predicts the minimum noise threshold to achieve a target fidelity. **74% accuracy**

This matters because simulating quantum circuits can take hours; a fast ML baseline lets you filter and prioritize which circuits are worth running.

**Stack:** Python, scikit-learn, QASM feature extraction, regression & classification.

<div style="margin: 1.2rem 0;">
  <a href="https://github.com/SoftLocked/2026-Quantum-Rings" target="_blank" style="display:inline-block;padding:0.5rem 1.3rem;background:var(--global-theme-color);color:#fff;border-radius:6px;font-weight:600;text-decoration:none;">💻 Code on GitHub</a>
</div>

---

<div class="row mt-2">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/MIT3.jpeg" title="Massachusetts Institute of Technology — iQuHACK 2026" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/MIT6.jpeg" title="iQuHACK 2026 — 3rd Place certificate, Quantum Rings Challenge" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>

<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;border-radius:8px;margin-top:1.5rem;margin-bottom:1.5rem;">
  <iframe src="https://www.youtube.com/embed/DH8juniPkKs?start=5436&autoplay=1&mute=1" title="MIT iQuHACK 2026 — Official Award Ceremony, Team Popeye's 3rd Place" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;"></iframe>
</div>

<div class="row mt-2">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/MIT7.jpg" title="Team Popeye's receiving 3rd Place — iQuHACK 2026 Quantum Rings Challenge" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/MIT1.JPG" title="3rd Place certificate — iQuHACK 2026 Quantum Rings Challenge" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>

<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/MIT2.jpeg" title="MIT campus in winter — iQuHACK 2026" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/MIT4.jpeg" title="Quantum hardware at MIT" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/MIT5.jpeg" title="iQuHACK 2026 — 400+ competitors at MIT" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
