---
title: Contact
nav:
  order: 9
  tooltip: Email, address, and location
  main: 1
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contacts

Baysan Lab and Çakmak Lab are part of Faculty of Computer And Informatics Engineering at Istanbul Technical University. Don't hesitate to contact us through any of the provided information. We will get back to you as soon as possible.

**Bioinformatics and Databases Lab Adress:**

İTÜ Ayazağa Campus, Faculty of Computer and Informatics, 34467 Sarıyer/Istanbul

{%
  include button.html
  type="email"
  text="Bioinformatic Research Group"
  link="bioinformatics@itu.edu.tr"
%}
{%
  include button.html
  type="email"
  text="Baysan Lab"
  link="baysanm@itu.edu.tr"
%}
{%
  include button.html
  type="email"
  text="Çakmak Lab"
  link="ali.cakmak@itu.edu.tr"
%}
{%
  include button.html
  type="address"
  text="Google Maps"
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
  image="images/itu.jpg"
  caption="Istanbul Technical University"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

