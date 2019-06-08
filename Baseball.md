---
layout: page
title: Baseball
permalink: /Baseball/
---

<ul>
  {% for post in site.posts %}
    {% if post.tag == "baseball"  %}

    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
      {{ post.brief }}

      {% endif %}
  {% endfor %}
</ul>
