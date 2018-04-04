---
layout: default
---

Here's my OzRunways `.ozacft` files.

{% for file in site.static_files %}
  {% if file.extname == ".ozacft" %}
 * [{{ file.basename }}]({{ site.sitepath }}{{ file.path }}) (Modified: {{ file.modified_time }})
  {% endif %}
{% endfor %}

**These are provided with absolutely no warranty whatsoever, and you absolutely must compare them with your aircraft's POH. Do not use these operationally, that would be very unwise and silly.**

You can contribute to this list here: [GitHub]({{ site.repo }}).