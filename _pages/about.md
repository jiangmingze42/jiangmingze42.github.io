---
permalink: /
title: "About Me"
browser_title: "Mingze Jiang"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am an undergraduate student at Tsinghua University. This website collects my research interests, publications, and other academic activities.

You can find my [CV](/files/0227%20MingzeJiang_CV.pdf) here.

## Research

My research interests lie at the intersection of artificial intelligence, computer vision, and biomedical imaging. I am particularly interested in developing robust, interpretable, and clinically reliable learning systems that can transform imperfect biomedical data into actionable evidence, with an emphasis on medical image restoration, multimodal understanding, and trustworthy decision-making under real-world variability.

{% include research-timeline.html %}

## Publications

{% for category in site.publication_category %}
{% assign publications_sorted = site.publications | sort: "date" %}
{% for post in publications_sorted %}
{% if post.category != category[0] %}
{% continue %}
{% endif %}
{% include publication-card.html %}
{% endfor %}
{% endfor %}

## Miscellaneous

### Awards & Honors

- 2025 Comprehensive Excellence Scholarship, Tsinghua University
- 2024 Comprehensive Excellence Scholarship, Tsinghua University
- 2023 Freshman Scholarship, Tsinghua University
- Tsinghua University Student Social Practice Silver Award

### Interests

I am passionate about figure skating and am a member of Tsinghua University's Figure Skating Club. I particularly enjoy watching figure-skating competitions and ice shows.
