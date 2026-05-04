---
title: Team
nav:
  order: 3
  tooltip: About our team
---

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %} Team

We're an interdisciplinary team of researchers working on cardiovascular epigenomics, gene regulation, and computational approaches for understanding disease mechanisms.

## Current lab members

{% include list.html data="members" component="portrait" filter="group == 'current' and role == 'pi'" %}

{% include list.html data="members" component="portrait" filter="group == 'current' and role == 'phd'" %}

{% include section.html dark=true %}

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Interested in joining us?"
  link="join"
  style="button"
%}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filter="group == 'alumni'" style="small" %}

{% include section.html %}

## Funding

{% capture content %}

[![University of Eastern Finland](https://sites.uef.fi/europeanforestry/wp-content/uploads/sites/62/2020/05/UEF_eng_pysty_1_black-1024x892.jpg)](https://www.uef.fi/fi)

{% endcapture %}

{% include grid.html content=content %}

{% include section.html %}
