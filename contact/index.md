---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

For more information about our research, data resources, or potential collaborations, please feel free to reach out.  
Prospective students and postdoctoral fellows are also encouraged to contact us with a brief description of their interests.

{%
  include button.html
  type="email"
  text="paudellab@gmail.com"
  link="paudellab@gmail.com"
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
  link="https://www.google.com/maps/place/345+Crispell+Dr,+Charlottesville,+VA+22908/@38.0311115,-78.5013875,17z/data=!3m1!4b1!4m6!3m5!1s0x89b3864742555555:0x957df2f1854b82c0!8m2!3d38.0311115!4d-78.4988126!16s%2Fg%2F11nnktfqmx?entry=ttu&g_ep=EgoyMDI1MTIwOS4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

### Mailing Address

**P3 (Predict, Perturb & Profile) Systems Biology Lab**  
Department of Medicine and Biomedical Engineering  
University of Virginia  
Carter Harrison Research Building (MR-6)- 617(A-B)  
345 Crispell Drive, Charlottesville, VA, USA, 22908  

{% endcapture %}

{% capture col2 %}

### Research & Collaboration

We are interested in collaborations related to:
- Systems biology and network modeling  
- Cancer metabolism and heterogeneity  
- Multi-omics data integration  
- Translational and computational approaches
- Health disparities
- Tool development

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
