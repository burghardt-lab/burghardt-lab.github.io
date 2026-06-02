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
{% include list.html data="members" component="portrait" filter="role == 'undergrad'" %}

{% include section.html %}

## Alumni

{% assign alums = site.members | where: "role", "alum" %}

{% assign phd_alums = alums | where: "description", "PhD Student" %}
{% assign ug_alums  = alums | where: "description", "Undergraduate Student" %}

{% assign ordered_alums = phd_alums | concat: ug_alums %}

{% include list.html
  data=ordered_alums
  component="portrait"
%}




