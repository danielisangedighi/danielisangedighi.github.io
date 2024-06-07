---
layout: page
title: "Blog"
---
<!-- # Blog -->

<ul>
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date: "%B %d, %Y" }}</span> - <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
