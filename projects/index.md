---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

This page highlights software tools, datasets, and research-driven resources developed to support data analysis, reproducibility, and integrative modeling. The projects span methodological development, computational workflows, and applied analyses, with an emphasis on transparency, usability, and impact across biomedical and quantitative research. We welcome feedback, comments on the usability of these tools.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
