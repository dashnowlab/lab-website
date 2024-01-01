---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

<!-- Insert text here -->

{%
  include button.html
  type="email"
  text="Email Harriet Dashnow"
  link="harriet.dashnow@cuanschutz.edu"
%}
{%
  include button.html
  type="phone"
  text="(303) 724-0343"
  link="+1-303-724-0343"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/WSRibxcLAHTUbG5X7"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/DBMIbuilding.jpg"
  caption="CU Department of Biomedical Informatics"
  link="https://medschool.cuanschutz.edu/dbmi/"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/classroom.jpg"
  caption="Biomedical Informatics PhD Programs"
  link="https://medschool.cuanschutz.edu/dbmi/education"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
<!-- 
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
-->
{% endcapture %}

{% capture col2 %}
<!-- 
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
-->
{% endcapture %}

{% capture col3 %}
<!-- 
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
-->
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
