---
type: Reading
---

# {{ page.type }}

<!-- Create a variable to point to the stars sprite -->
{% assign ss = "/assets/images/star-rating-sprite.png" %}

{% capture star1 %}
<span style="display: inline-block; width: 65px; height: 13px; background: url({{ ss }}) 0 0;">
  <span style="display: block; width: 20%; height: 13px; background: url({{ ss }}) 0 -13px;">
  </span>
</span>
{% endcapture %}

{% capture star2 %}
<span style="display: inline-block; width: 65px; height: 13px; background: url({{ ss }}) 0 0;">
  <span style="display: block; width: 40%; height: 13px; background: url({{ ss }}) 0 -13px;">
  </span>
</span>
{% endcapture %}

{% capture star3 %}
<span style="display: inline-block; width: 65px; height: 13px; background: url({{ ss }}) 0 0;">
  <span style="display: block; width: 60%; height: 13px; background: url({{ ss }}) 0 -13px;">
  </span>
</span>
{% endcapture %}

{% capture star4 %}
<span style="display: inline-block; width: 65px; height: 13px; background: url({{ ss }}) 0 0;">
  <span style="display: block; width: 80%; height: 13px; background: url({{ ss }}) 0 -13px;">
  </span>
</span>
{% endcapture %}

{% capture star5 %}
<span style="display: inline-block; width: 65px; height: 13px; background: url({{ ss }}) 0 0;">
  <span style="display: block; width: 100%; height: 13px; background: url({{ ss }}) 0 -13px;">
  </span>
</span>
{% endcapture %}

## 2020

Reserved for keeping a list of books I've read...

- {{ star1 }}
- {{ star2 }}
- {{ star3 }}
- {{ star4 }}
- {{ star5 }}
