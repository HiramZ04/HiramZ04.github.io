---
layout: page
title: Medical Insurance Prediction
description: ML-powered web app predicting medical insurance charges from demographic and health features.
img: assets/img/InsuranceThumb.png
importance: 8
category: research
related_publications: false
---

A web app that predicts medical insurance costs from patient demographics and health indicators (age, BMI, smoker status, region). The ML model runs inference on form inputs and returns an estimated cost with a visual risk-level indicator. Covers the full lifecycle: EDA, feature engineering, model selection, and deployment.

**Stack:** scikit-learn, pandas, Python, React.

<div style="margin: 1.2rem 0;">
  <a href="https://github.com/HiramZ04/medical-insurance-prediction" target="_blank" style="display:inline-block;padding:0.5rem 1.3rem;background:var(--global-theme-color);color:#fff;border-radius:6px;font-weight:600;text-decoration:none;">💻 Code on GitHub</a>
</div>

---

<div class="row mt-2">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/insurance2.png" title="Input form — patient demographics and health factors" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/insurance3.png" title="Estimated cost result with risk-level gradient" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
