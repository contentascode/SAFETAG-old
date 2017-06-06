[![]({{logo}})]({{website}})
 - Website: {{website}}
 - Download: {% for item in downloads %}
   - [{{ item.label }}]({{ item.url }})
{%- endfor %}
 - Version: {{version}}
 - License: {{license}}

{{ contents }}
