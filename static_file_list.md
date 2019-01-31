---
permalink: /staticlist
---

# Static files and images
  Not for audience  
  For developers

{% for file in site.static_files %}
| Path | Name|
| --- | --- |
  {{ file.path }}    |    {{ file.name }}
{% endfor %}
