---
title: P3 Systems Biology Lab
display_title: P<sup>3</sup> Systems Biology Lab
layout: default
---

<div style="display: grid; grid-template-columns: 1fr 300px; gap: 3rem; align-items: start;">
  <main>
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
  </main>

  <aside style="border: 1px solid #ddd; padding: 1.5rem; border-radius: 8px; background-color: #f9f9f9; position: sticky; top: 20px;">
    <h3 style="margin-top: 0; border-bottom: 2px solid #007bff; padding-bottom: 0.5rem;">Latest News</h3>
    {% assign sorted_posts = site.posts | sort: 'date' | reverse %}
    {% for post in sorted_posts limit:3 %}
      <div style="margin-bottom: 1.5rem; padding-bottom: 1rem; border-bottom: 1px solid #eee;">
        <p style="margin: 0; font-weight: bold;"><a href="{{ post.url | relative_url }}" style="color: #007bff; text-decoration: none;">{{ post.title }}</a></p>
        <p style="margin: 0.3rem 0 0 0; font-size: 0.9rem; color: #666;">{{ post.date | date: "%b %d, %Y" }}</p>
      </div>
    {% endfor %}
    <p style="margin: 1rem 0 0 0; text-align: center;">
      <a href="blog/" style="color: #007bff; text-decoration: none; font-weight: bold;">View all news →</a>
    </p>
  </aside>
</div>
