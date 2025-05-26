---
title: 友情链接
layout: page
---
# 友情链接

<ul>
  {% for friend in site.data.friends %}
    <li>
      <a href="{{ friend.url }}" target="_blank" rel="noopener">{{ friend.name }}</a>
      — {{ friend.desc }}
    </li>
  {% endfor %}
</ul>
