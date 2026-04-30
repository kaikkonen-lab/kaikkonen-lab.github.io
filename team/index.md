---
title: Team
nav:
  order: 3
  tooltip: About our team
---

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Team

We're an interdisciplinary team of researchers who strive to be rigorous, reproducible, and transparent. Our core values include learning from each other and celebrating the success of others.

## Current lab members

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}


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

{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}



## Funding

{% capture content %}

[![University of Eastern Finland](https://sites.uef.fi/europeanforestry/wp-content/uploads/sites/62/2020/05/UEF_eng_pysty_1_black-1024x892.jpg)](https://www.uef.fi/fi)


{% endcapture %}

{% include grid.html content=content %}

{% include section.html %}

{%
  include figure.html
  image="images/group3.jpg"
  caption="Kaikkonen lab summer 2025"
  width="80%"
%}

{%
  include figure.html
  image="images/group2.jpg"
  caption="Kaikkonen lab winter 2025"
  width="80%"
%}
