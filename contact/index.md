---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Assoc. Prof. Mehmet Baysan's group (BaysanLAB) is part of Faculty of Computer And Informatics Engineering at Istanbul Technical University. 

{%
  include button.html
  type="email"
  text="Assoc. Prof. Mehmet Baysan"
  link="baysan@gmail.com"
%}
{%
  include button.html
  type="Google Maps"
  tooltip="Our location on Google Maps at ITU"
  link="https://goo.gl/maps/LSHJ3zbvkp97XWBA6"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/faculty.jpg"
  caption="Computer & Informatics Faculty"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
