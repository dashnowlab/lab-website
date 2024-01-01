---
title: Team
nav:
  order: 3
  tooltip: About our team
---



We are currently recruiting postdocs, staff scientists and students. If you're passionate about rare disease genomics and computational method development, please get in touch!

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/classroom.jpg"
  caption="Biomedical Informatics PhD Programs"
  link="https://medschool.cuanschutz.edu/dbmi/education"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/DBMIbuilding.jpg"
  caption="Employment Opportunities at CU Biomedical Informatics"
  link="https://medschool.cuanschutz.edu/dbmi/employment"
%}

{% endcapture %}


{% include cols.html col1=col1 col2=col2 %}

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

# Values

- **Kindness**
- **Diversity**
- **Collaboration**
- **Open Science**


{% include section.html %}





