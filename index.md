---
layout: default
title: Home
---

# Welcome

Sharing random topics all related to malware. Stay tuned for the latest updates.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
