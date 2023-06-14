---
title: Teams
nav:
  order: 5
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Baysan Lab Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: master" %}
{% include list.html data="members" component="portrait" filters="role: undergrad" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Çakmak Lab Team

{% include section.html %}

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
