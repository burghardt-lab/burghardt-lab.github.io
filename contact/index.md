---
title: Contact
nav:
  order: 5
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

If you are interested in joining the lab, please review information on [this page](https://burghardt-lab.github.io/join/). You can find us at 68th Street Hunter North 626C.

{%
  include button.html
  type="email"
  text="nb844@hunter.cuny.edu"
  link="nb844@hunter.cuny.edu"
%}
{%
  include button.html
  type="phone"
  text="(212) 396-6850"
  link="+1212 396-6850"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/qFXGnbieuNAgNNCw7"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/Hunter college sky bridge.jpg"
  caption="Hunter College"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/Hunter north building.jpg"
  caption="North Building"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}
