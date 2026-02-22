---
title: Research
nav:
  order: 1
  tooltip: Published works
highlighted:
  - doi:10.1182/bloodadvances.2023010535
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

Our research uses a systems bioengineering approach to investigate how aberrant signaling leads to distinct metabolic and epigenetic states, and to devise strategies for therapeutic reprogramming. P<sup>3</sup>SystemsBiology lab is interested in two main research areas: (1) network-level regulation of metabolic heterogeneity and (2) oncogene-induced alterations in the epigenome and cancer phenotypes. We integrate bioengineering, mechanistic and statistical modeling with single-cell and population-level experiments to identify metabolic vulnerabilities and drivers of early cancer progression. The long-term objective of our research program is to gain a predictive understanding of how dysregulated signaling generates specific metabolic and epigenetic states and how these states can be reprogrammed for therapeutic benefit. The lab prides itself in interdisciplinary focus in biological and quantitative sciences, combined with significant experience leading collaborative teams, and is positioned to tackle complex questions at the intersection of cancer biology, computational bioengineering, and quantitative systems pharmacology.

{% include section.html %}

## Highlighted

{% for item in page.highlighted %}
  {% include citation.html lookup=item style="rich" %}
{% endfor %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

<div markdown="0">
  {% include list.html data="citations" component="citation" style="rich" %}
</div>
