---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

<ul>
{% for person in site.people %}
<li>
<h3>{{ person.title }}</h3>
<p>Employee: <strong>{{ person.employee }}</strong></p>
<p>Alumni: <strong>{{ person.alumni }}</strong></p>
</li>
{% endfor %}
</ul>
