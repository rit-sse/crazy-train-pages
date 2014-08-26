---
title: About The SSE
permalink: about/minutes/
---

{% for minutes in site.meeting_minutes %}
  <a href='/about/minutes/{{minutes.date | date: "%Y-%m-%d"}}/'>{{ minutes.date | date: "%B %d, %Y" }}</a>
  <br>
{% endfor %}