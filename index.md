---
title: P3 Systems Biology Lab
display_title: P<sup>3</sup> Systems Biology Lab
---

{% capture text %}

Welcome to the **Paudel Lab** at the University of Virginia Comprehensive Cancer Center. We develop **data-driven and systems biology approaches** to understand cancer metabolism, drug response, and cellular heterogeneity by integrating multi-omics data, computational modeling, and experimental measurements. The long-term objective of our research program is to gain a predictive understanding of how dysregulated signaling (altered metabolism, transport, etc.) gives rise to emergent cancer phenotypes and their associated vulnerabilities.

{% endcapture %}

{%
  include feature.html
  image="images/Logo_Paudel.png"
  title=page.display_title
  text=text
%}

{% include section.html %}

## Highlights

{% capture text %}

Our research focuses on **integrating transcriptomics, proteomics, lipidomics, and functional assays** to build quantitative models of cancer cell behavior. We are particularly interested in emergent cancer phenotypes and how signaling network states shape therapeutic response and resistance.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/P3_Theme.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

We develop and apply **computational tools**, statistical frameworks, and network-based models to analyze complex biological datasets. Our projects span **experimentation, multi-modal data integration, metabolic network modeling, and statistical modeling for predictive signatures** that support translational cancer research.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Paudel_R1.png"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Our lab brings together researchers with backgrounds in **biology, data science, engineering, and medicine**. We value collaboration, mentorship, and rigorous quantitative thinking, and we are always excited to work with motivated students and trainees.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/p3lab_summer_2026.jpeg"
  link="team"
  title="Our Team"
  text=text
%}

{% include section.html %}

## Latest News

<div markdown="0" style="display: grid; grid-template-columns: 2fr 1fr; gap: 2rem;">
  <div>
    <p>For the latest updates from our lab, visit our <a href="blog/">full news page</a> to see all announcements, publications, and lab highlights.</p>
  </div>
  <aside style="border-left: 3px solid #007bff; padding-left: 1rem;">
    <h3>Recent Updates</h3>
    {% assign sorted_posts = site.posts | sort: 'date' | reverse %}
    {% for post in sorted_posts limit:3 %}
      <p style="margin: 0.5rem 0;">
        <strong><a href="{{ post.url | relative_url }}">{{ post.title }}</a></strong><br>
        <small>{{ post.date | date: "%b %d, %Y" }}</small>
      </p>
    {% endfor %}
    <p style="margin-top: 1rem;">
      <a href="blog/">→ View all news</a>
    </p>
  </aside>
</div>
