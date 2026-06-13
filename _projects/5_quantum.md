---
layout: page
title: QAOA Portfolio Optimizer
description: Quantum Approximate Optimization Algorithm applied to premium investment portfolio allocation. YQuantum (Yale) — 3rd place.
img: assets/img/yale1.jpg
importance: 1
category: hackathon
related_publications: false
images:
  - path: assets/img/yale1.jpg
    title: 3rd place — Challenge 6, Optimization of Premium Investment Portfolios
  - path: assets/img/yale5.jpg
    title: The team at YQuantum 2026
  - path: assets/img/yale2.jpg
    title: Welcome to YQuantum 2026, Yale
  - path: assets/img/yale3.jpg
    title: QAOA circuit design on the board
  - path: assets/img/yale4.jpg
    title: Problem formulation and Hamiltonian design
  - path: assets/img/yale6.jpg
    title: Yale campus
---

Applied the Quantum Approximate Optimization Algorithm (QAOA) to the problem of premium investment portfolio allocation — finding optimal asset combinations under real-world constraints. Built end-to-end in under 48 hours at Yale's **YQuantum 2026** hackathon. **3rd place overall**, Challenge 6: Optimization of Premium Investment Portfolios.

{% include figure.liquid loading="eager" path="assets/img/yale1.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}

{% if page.images %}
<div class="row mt-3">
{% for image in page.images offset:1 %}
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path=image.path title=image.title class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
{% endfor %}
</div>
{% endif %}

**Stack:** Qiskit, QAOA, Python, portfolio optimization.

[Live site](https://yquantum-webpage.vercel.app/) · [Code on GitHub](https://github.com/ilayd-a/Optimization-of-Premium-Investment-Portfolios)
