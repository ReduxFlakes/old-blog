---
title: Apps
permalink: /apps/
layout: default
---

# Android Apps

I occasionally make apps for Android and make them open source. This page contains _all_ of my apps (with active development).

<ul class="card-item card-sm">
  {% for item in site.data.apps %}
  <li>
    <a href="{{ item.app_resume }}">
      <h2>{{ item.app_name }}{% if item.app_comingsoon %}<span>{{ item.app_comingsoon }}</span>{% endif %}
</h2>
      <p>{{ item.app_summary }}</p>
    </a>
  </li>
  {% endfor %}
</ul>
