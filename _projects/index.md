---
type: index
---

# Projects

I'll be listing various personal projects here...

<ul>
{% for project in site.projects %}
  {% if project.type != 'index' %}
    <li><a href="{{ project.url }}">{{ project.type }}</a></li>
  {% endif %}
{% endfor %}
</ul>
