---
permalink: /
title: "About Me"
browser_title: "Mingze Jiang"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a rising senior in Computer Science at Tsinghua University. My research has exposed me to a range of problems in artificial intelligence, computer vision, and biomedical imaging through work at MIT and the University of Notre Dame. I am particularly interested in research that connects methodological advances with meaningful scientific questions, and in how machine learning can provide better ways to measure, represent, and understand complex data.

I am actively seeking PhD opportunities for Fall 2027.

You can find my [CV](/files/0227%20MingzeJiang_CV.pdf) here.

## Research

My research lies at the intersection of artificial intelligence, computer vision, and biomedical imaging. I am interested in developing computational methods that extract reliable and biologically meaningful information from complex biomedical data. More broadly, I hope to build learning systems that are not only accurate, but also scientifically interpretable and reliable in real-world biomedical settings.

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
