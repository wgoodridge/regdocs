---
title: Test-3
layout: default
url: /pages/test-3.html

colors:
  - red
  - blue
  - green
---
# {{page.title}}
This is Test-3 page.

<ul>
<li>my item </li>
{% for item in site.data.toc.groups %}
  <li> {{ item.title }} </li>
{% endfor %}  

</ul>
