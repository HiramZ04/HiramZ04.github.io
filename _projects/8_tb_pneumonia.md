---
layout: page
title: TB & Pneumonia Classifier
description: CNN-based web app for tuberculosis and pneumonia detection from chest X-rays, with patient management dashboard.
img: assets/img/PneumoniaThumb.jpeg
importance: 11
category: research
related_publications: false
---

A full-stack clinical tool for multi-class detection of tuberculosis and pneumonia from chest X-ray images. The CNN backend classifies scans in single or batch mode, outputs class probabilities, and attaches results to a patient management dashboard — designed around a real doctor workflow.

**Stack:** PyTorch, CNNs, medical imaging, Python, React.

<div style="margin: 1.2rem 0;">
  <a href="https://github.com/andres-go/tuberculosis-pneumonia-classifier" target="_blank" style="display:inline-block;padding:0.5rem 1.3rem;background:var(--global-theme-color);color:#fff;border-radius:6px;font-weight:600;text-decoration:none;">💻 Code on GitHub</a>
</div>

---

<div class="row mt-2">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/neumonia4.png" title="MRI Scan Classifier — upload screen" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/neumonia1.png" title="Single scan result — Pneumonia detected (61.5% confidence)" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>

<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/nuemonia2.png" title="Single scan result — Tuberculosis detected (37.8% confidence)" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/neumonia3.png" title="Patients dashboard — scan history and results per patient" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
