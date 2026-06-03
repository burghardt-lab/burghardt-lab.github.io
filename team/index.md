---
title: Team
nav:
  order: 3
---

# {% include icon.html icon="fa-solid fa-people-group" %}Team


## Current Members

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'lab-manager'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad'" %}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filter="role == 'alum-phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'alum-undergrad'" %}




