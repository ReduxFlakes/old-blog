---
title: Extra
layout: single
---

<div class="pod" markdown=1>

# Extra

Additional links and pages that are not that _special_ to be on the navbar and not because there's no space in the navigation menu.

<ul class="card-item card-sm">
  {% for item in site.data.extra %}
  <li>
    <a href="{{ item.url }}">{{ item.name }}</a>
    <span>- {{ item.description }}</span>
  </li>
  {% endfor %}
</ul>

</div>
