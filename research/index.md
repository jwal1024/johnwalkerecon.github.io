---
layout: default
title: Research
---

# Research

{% if site.research and site.research.size > 0 %}
  {% for item in site.research %}
    <section>
      <h3>{{ item.title }}</h3>
      {{ item.content }}
    </section>
  {% endfor %}
{% else %}
  <p>No research items yet.</p>
{% endif %}
