---
layout: default
title: Research
---

# Research

{% if site.research and site.research.size > 0 %}
  <ul>
    {% for item in site.research %}
      <li>
        <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
      </li>
    {% endfor %}
  </ul>
{% else %}
  <p>No research items yet.</p>
{% endif %}
