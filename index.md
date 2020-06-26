---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# This site is dedicated to cataloging anything what I'm passionate about.
---

# Interests

<ul>
{% for interest in site.interests %}
<li><a href="{{ interest.url }}">{{ interest.type }}</a></li>
{% endfor %}
</ul>

# Contact

jan at markowski dot ca.
