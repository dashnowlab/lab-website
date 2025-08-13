---
title: Team
nav:
  order: 3
  tooltip: About our team
---

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html %}

# Values

- **Kindness**: We encourage a culture of empathy, respect, and support, where individuals actively contribute to a positive and inclusive environment.
- **Diversity**: We are a team with diverse backgrounds, experiences and perspectives. We beleive that diversity fosters creativity, innovation, and fairness.
- **Collaboration**: We partner with clinicians, researchers and industry partners to benefit patients, achieve common scientific goals, and address complex challenges.
- **Open Science**: We believe that sharing knowledge openly accelerates scientific progress. We are dedicated to making our research data, software, and findings accessible to the global scientific community.


{% include section.html %}

# Join us

Applications are welcome for postdocs, staff scientists and students. If you're passionate about rare disease genomics and computational method development, please get in touch!

- **Postdoc** candidates please email Harriet Dashnow and include:
  - A summary of your career and research goals
  - Why you would like to join this lab and how your research would complement ours
  - A CV including referees
- **Students** 
  - Current CU students: we are open to rotation requests from PhD and MD/PhD students.
  - Future CU graduate research students should apply through one of the graduate programs described below. Please reach out if you are applying with the goal of joining our lab specifically.
  - Part-time or summer positions may be available for students in coursework programs.

For all other positions, please reach out to Harriet Dashnow to discuss options.

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



