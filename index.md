---
title: Blogging Like a Hacker
---

{{ page.title }}

{% for site in site.data.sites %}
      [{{ site.name }}]({{ site.name }})
{% endfor %}
