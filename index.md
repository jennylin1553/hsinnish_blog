---
title: Light and the Owl
---

從前從前，有一座孤島，島上有光，還棲息了一隻貓頭鷹。

>>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
