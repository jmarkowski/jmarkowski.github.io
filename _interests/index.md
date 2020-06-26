---
type: index
---

# Interests

<ul>
{% for interest in site.interests %}
  {% if interest.type != 'index' %}
    <li><a href="{{ interest.url }}">{{ interest.type }}</a></li>
  {% endif %}
{% endfor %}
</ul>
