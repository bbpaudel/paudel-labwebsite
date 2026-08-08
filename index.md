---
title: P3 Systems Biology Lab
display_title: P<sup>3</sup> Systems Biology Lab
layout: default
---

<div style="display: grid; grid-template-columns: 1fr 300px; gap: 1.5rem; align-items: start;">
  <main>
    {% capture text %}

Welcome to the **Paudel Lab** at the University of Virginia Comprehensive Cancer Center. A central premise of our work is that understanding and disrupting these adaptive processes requires a systems-level approach—one that reveals how dysregulated signaling establishes biochemical states that drive long-term cell fate decisions and clinically relevant phenotypes. The long-term objective of our research program is to develop a predictive understanding of how dysregulated signaling states emerge, how they alter metabolic and epigenetic programs, and how these signaling states can be reprogrammed for therapeutic benefit. 

    {% endcapture %}

    {%
      include feature.html
      image="images/Logo_Paudel.png"
      title=page.display_title
      text=text
    %}

    {% include section.html %}

    {% capture text %}

Our research focuses on **integrating transcriptomics, proteomics, lipidomics, and functional assays** to build quantitative models of cancer cell behavior. We aim to develop generalizable frameworks that combine experimental systems, bioengineering, computational modeling, and bioinformatics. Using classic systems biology approach, our vision is to use these frameworks to enable the identification of cellular mechanisms governing divergent cell fates, metabolic homeostasis, and responses to perturbation. 


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
      stack=true
    %}

    {% capture text %}

We develop and apply **computational tools**, statistical frameworks, and network-based models to analyze complex biological datasets. Our projects span experimentation, multi-modal data integration, mathematical modeling to investigate how cellular signaling is disrupted in cancer cells, how these alterations lead to emergent cancer phenotypes. 

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
      stack=true
    %}

    {% capture text %}

Our lab brings together researchers with backgrounds in **biology, data science, engineering, and medicine**. We value collaboration, mentorship, and rigorous quantitative thinking, and we are always looking for enthusiastic and motivated members to join our group.  

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
      stack=true
    %}
  </main>

  <aside style="border: 1px solid #ddd; padding: 1.5rem; border-radius: 8px; background-color: #f9f9f9; position: sticky; top: 20px;">
    <h3 style="margin-top: 0; border-bottom: 2px solid #007bff; padding-bottom: 0.5rem;">Latest News</h3>
    {% assign sorted_posts = site.posts | sort: 'date' | reverse %}
    {% for post in sorted_posts limit:5 %}
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

