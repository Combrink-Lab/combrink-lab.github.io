---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We welcome, embrace, and are strengthened by diverse views and experiences of all team members. Our lab is comprised of compassionate scientists who foster a welcoming, inclusive, and healthy environment. We define success individually for each team member, and we challenge each other to develop and pursue individual passions.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}
