---
title: Light and the Owl
---

從前從前，有一座孤島，島上有光，還棲息了一隻貓頭鷹。

>>

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
