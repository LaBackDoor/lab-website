---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

{%
  include button.html
  type="email"
  text="support@labackdoor.com"
  link="support@labackdoor.com"
%}
{%
  include button.html
  type="address"
  text="Baylor University"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/w3KDHkNoSrUmtYmu7"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/dog.svg"
%}

{% endcapture %}

{% include cols.html col1=col1 %}

{% include section.html dark=true %}


