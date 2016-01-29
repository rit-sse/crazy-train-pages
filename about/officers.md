---
title: Officers
permalink: about/officers/
---
Minutes from weekly Officers meetings are
[available here](https://drive.google.com/a/g.rit.edu/folderview?id=0ByJTmmqthU2scDZjRFRLakVzaTA&usp=sharing). (requires RIT login)

### Principal Officers

{% for officer in site.data.primary_officers %}
  {{officer.name}}, {{officer.position}}
  <br>
  <{{officer.email}}@sse.se.rit.edu>
{% endfor %}

### Committee Heads

{% for officer in site.data.committee_heads %}
  {{officer.name}}, {{officer.position}}
  <br>
  <{{officer.email}}@sse.se.rit.edu>
{% endfor %}
