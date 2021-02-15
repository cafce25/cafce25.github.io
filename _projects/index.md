---
layout: default
permalink: /projects
---
# Projects
{% for proj in site.projects %}
{% if proj.title != "Index" %}
[{{ proj.title }}]({{ proj.url }})
{% endif %}
{% endfor %}

