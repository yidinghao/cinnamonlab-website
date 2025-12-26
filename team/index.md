---
title: People
nav:
  order: 3
  tooltip: Lab members
---

# {% include icon.html icon="fa-solid fa-users" %}People

Cinnamonlab members come from BU’s Department of Linguistics and Faculty of Computing and Data Sciences, as well as external institutions. Members include Sophie and her advisees as well as other researchers working with Cinnamonlab members.

{% include section.html %}
{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}
