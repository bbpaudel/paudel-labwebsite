---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a systems biology group with team members coming from diverse academic backgrounds. Our research team employs complementary experimental and computational approaches to establish a systems biology framework linking altered biochemical states with metabolic adaptation, therapeutics, and tumorigenesis.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include section.html %}

## Alumni

We are grateful to the many students, trainees, and researchers who have contributed to our work and have gone on to pursue diverse career paths.

{% include list.html data="alumni" component="portrait" %}

{% include section.html %}

## Collaborators

We work closely with collaborators across disciplines including systems biology, metabolism, computation, and clinical research.

{% include list.html data="collaborators" component="portrait" %}
