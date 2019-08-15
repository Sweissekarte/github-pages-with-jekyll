---
title: Front Page
---
# Welcome to the Head cheese Blog

I'm glad you are here. I plan to talk about a lot of stuff.


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
