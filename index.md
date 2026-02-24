---
title: Home
layout: home
---

"Writings on the Board" is a collection of (in)evitable Whys.

<ul class="posts">
   {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
   {% endfor %}
</ul>
