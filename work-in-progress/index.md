---
layout: default
title: Work in Progress
---

# Work in Progress

{% if site.work-in-progress and site.work-in-progress.size > 0 %}
  <ul>
    {% for item in site.work-in-progress %}
      <li>
        <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
      </li>
    {% endfor %}
  </ul>
{% else %}
  <p>No work-in-progress items yet.</p>
{% endif %}
