---
layout: page
title: Personas
info: Examples of Varity Peronas
---

<div class="tiles">
{% for page in site.pages %}
  {% for pc in page.categories %}
    {% if pc == 'persona' %}
      {% include page-grid.html %}
    {% endif %}
  {% endfor %}
{% endfor %}
</div>