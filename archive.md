---
layout: default
title: My first blog post!
---

##Blog Posts
{% for post in site.posts %}
  *{{ post.date | date_to_string }} &raquo; [ {{ post.title }}]({{ post.url}})
{% endfor %}