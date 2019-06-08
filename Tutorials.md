---
layout: page
title: tutorials
permalink: /tutorials/
---


<ul>
  {% for post in site.posts %}
    {% if post.tag == "tutorial" %}

    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
      {{ post.brief }}
      {% endif %}
  {% endfor %}
</ul>
