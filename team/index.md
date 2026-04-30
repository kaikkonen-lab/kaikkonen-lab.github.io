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
{% include list.html data="members" component="portrait" filters="role: ms, group: " %}

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
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: ms, group: alum" style="small" %}

## Funding

{% capture content %}

[![BC Children's Hospital Foundation](https://www.bcchr.ca/sites/default/files/microsites/logos/bcchf--logo_0.png)](https://www.bcchf.ca/)

[![Natural Sciences and Engineering Research Council of Canada](/images/NSERC_RGB.jpg)](https://www.nserc-crsng.gc.ca/)

[![Canadian Statistical Sciences Institute](https://i0.wp.com/canssi.ca/wp-content/uploads/CANSSI_Logo.png?resize=1024%2C1024&ssl=1)](https://canssi.ca/)

[![Canadian Institutes
of Health Research](https://cihr-irsc.gc.ca/images/leaf-cihr-colour-en.jpg)](https://cihr-irsc.gc.ca/)

{% endcapture %}

{% include grid.html content=content %}

{% include section.html %}

{%
  include figure.html
  image="images/group3.jpg"
  caption="Korthauer lab winter social 2024"
  width="80%"
%}

{%
  include figure.html
  image="images/group2.jpg"
  caption="Korthauer lab summer social 2023"
  width="80%"
%}
