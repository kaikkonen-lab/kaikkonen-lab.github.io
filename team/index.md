---
title: Team
nav:
  order: 3
  tooltip: About our team
---

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Team

We're an interdisciplinary team of researchers who strive to be rigorous, reproducible, and transparent. Our core values include learning from each other and celebrating the success of others.

{% include section.html  background="images/background.jpg" dark=true %}

## Current lab members

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
