---
layout: default
title: Teaching
---

# Teaching

{% if site.teaching and site.teaching.size > 0 %}
  <ul>
    {% for item in site.teaching %}
      <li>
        <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
      </li>
    {% endfor %}
  </ul>
{% else %}
  <p>No teaching items yet.</p>
{% endif %}
