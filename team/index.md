---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are systems biology group with team members coming from diverse academic backgrounds. Our research team employs complementary experimental and computational approaches to establish a systems biology framework linking altered biochemical states with metabolic adaptation, therapeutics, and tumorigenesis.
.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

We are always interested in working with motivated individuals with interests in pursuing interdisciplinary research.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
