---
layout: default
permalink: /projects
---
# Projects
{% for proj in site.projects %}
{% if proj.title != "Index" %}
[{{ proj.name }}]({{ proj.url }})
{% endif %}
{% endfor %}

