---
title: "All COGA Objectives"
permalink: "/objectives/"
---

Objectives are used to group the <a href="{{ '/patterns' | relative_url'}}">patterns</a>.

<ul>
{% for objective in site.objectives %}
  <li><a href="{{ objective.url | relative_url }}">{{ objective.title }}</a></li>
{% endfor %}
</ul>