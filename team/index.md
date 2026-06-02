---
title: Team
nav:
  order: 3
---

# {% include icon.html icon="fa-solid fa-people-group" %}Team

{% include section.html %}

## Current Members

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'lab-manager'" %}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filter="role == 'alum'" sort="description" %}



