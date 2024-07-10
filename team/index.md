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
  caption="View open positions at DBMI"
  link="https://medschool.cuanschutz.edu/dbmi/employment"
%}

{% endcapture %}


{% include cols.html col1=col1 col2=col2 %}

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

# Values

- **Kindness**: We encourage a culture of empathy, respect, and support, where individuals actively contribute to a positive and inclusive environment.
- **Diversity**: We are a team with diverse backgrounds, experiences and perspectives. We beleive that diversity fosters creativity, innovation, and fairness.
- **Collaboration**: We partner with clinicians, researchers and industry partners to benefit patients, achieve common scientific goals, and address complex challenges.
- **Open Science**: We believe that sharing knowledge openly accelerates scientific progress. We are dedicated to making our research data, software, and findings accessible to the global scientific community.


{% include section.html %}





