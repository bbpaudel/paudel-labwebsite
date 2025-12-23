---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
header: images/P3_Theme.jpg
header-dark: true
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

For more information about our research, data resources, or potential collaborations, please feel free to reach out.  
Prospective students and postdoctoral fellows are also encouraged to contact us with a brief description of their interests.

{%
  include button.html
  type="email"
  text="bp5sq@virginia.edu"
  link="bp5sq@virginia.edu"
%}
{%
  include button.html
  type="email"
  text="p3sysbiolab@gmail.com"
  link="p3sysbiolab@gmail.com"
%}
{%
  include button.html
  type="address"
  tooltip="View our location on Google Maps"
  link="https://www.google.com/maps/place/University+of+Virginia"
%}

{% include section.html %}

{% capture col1 %}

### Mailing Address

**P3 (Predict, Perturb & Profile) Systems Biology Lab**  
Department of Medicine and Biomedical Engineering  
University of Virginia  
Charlottesville, VA, USA

{% endcapture %}

{% capture col2 %}

### Research & Collaboration

We are interested in collaborations related to:
- Systems biology and network modeling  
- Cancer metabolism and AML  
- Multi-omics data integration  
- Translational and computational approaches  

Please include relevant background or project ideas when reaching out.

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}

### Prospective Students

Graduate students interested in rotations or thesis research should include:
- A brief statement of interest  
- Relevant coursework or experience  

{% endcapture %}

{% capture col2 %}

### Postdoctoral Fellows

Postdoctoral applicants should include:
- CV  
- Brief summary of research interests  
- Names of potential referees  

Funding opportunities may be available through institutional and external funding mechanisms.

{% endcapture %}

{% capture col3 %}

### Data & Software

For access to software, datasets, or code developed by the lab, please visit our GitHub page or contact us directly with specific questions.

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
